# Refuge vivant — prototype Android 0.5.0

Compagnons fantastiques, soins, refuge, invitations libres et relations persistantes. Aucun compte ni achat dans le jeu.

[Télécharger 0.5.0](https://raw.githubusercontent.com/maxstg7-wq/refuge-vivant-downloads/main/refuge-vivant-phase1-arm64.apk?v=0.5.0)

![QR du dernier APK](qr-android.png)

Le QR conserve sa cible historique `refuge-vivant-phase0-arm64.apk`, identique à l’alias phase1 : **0.5.0/code7**. Le laboratoire original est archivé séparément ; ne pas réinstaller une ancienne version après migration.

## Installer

Android7/API24 minimum, système **arm64-v8a**. Installer **par-dessus** Refuge vivant, sans désinstaller ni effacer ses données. Même identifiant `org.refugevivant.lab` et certificat de test conservé. Les sauvegardes du laboratoire et du monde2 migrent vers monde3 ; SQLite3 demeure. Aucun compte GitHub requis pour télécharger l’APK.

## Jouer

Le refuge occupe l’écran. Toucher la porte pour le jardin, le panier pour l’atelier et les panneaux pour revenir. Choisir un compagnon puis toucher un objet, ou l’approcher du compagnon.

- Repas : apporter trois bouchées d’une portion vers sa bouche.
- Bain : frotter six traces de terre. Câlin : trois longues caresses. Balle : trois lancers vers des cibles changeantes.
- Une seule commande de soin est sauvegardée à la fin ; un geste raté ne dépense rien. Les refus, le sommeil et les plafonds restent respectés. Partie/câlin pour le plaisir sans nouveau gain lorsque permis.
- Jardin : fleurs sauvages, trois cultures gratuites à planter/arroser/récolter sans expiration. Maison : Aménager pour fabriquer et déplacer trois créations persistantes.
- Atelier : verser les ingrédients dans le flacon, tourner le mélange, puis emporter le parfum au jardin. Les visiteurs viennent et repartent librement. Première visite d’un nouveau refuge après deux minutes simulées ; aucune remise à zéro des anciens mondes.
- Pour les activités à deux, sélectionner un compagnon puis déposer balle/banc sur un autre au jardin. Les préférences et le consentement sont conservés.
- Les arrivées/amitiés ont une courte scène souvenir ; le carnet illustré conserve les rencontres. Sac, fiches et options sont secondaires.

## Widget Android

Dans **⋯ → Ajouter le compagnon sur l’accueil**, ajouter le widget. Décor jour/nuit, horloge, clignement discret, besoins enregistrés et nouvelles. Nouvelles change de carte ; Pause/Animer contrôle le mouvement ; Repas ouvre le jeu sans dépense. Sommeil/mouvement réduit/économie d’énergie imposent une image fixe. Dernier état reçu seulement, sans second moteur ; rafraîchissement demandé30min, différable par Android et animation dépendante du lanceur. Si ancien layout en cache, retirer seulement le widget et le rajouter.

## Vérifié et limites

**61 tests TypeScript/SQLite/présentation et dix tests natifs Kotlin réussis.** APK Release arm64 compilé, même certificat, version7/API24+, bundle Hermes et43 PNG référencés vérifiés. Aucun overlay, paiement, service permanent ou alarme exacte.

Émulateur Android10 logiciel : habitat affiché et activité repas ouverte sur un build intermédiaire. ANR de System UI et corruption graphique ; parcours gestuel complet non validé. Mise à jour finale dans cet émulateur : délai expiré, lancement blanc lors du contrôle. **Aucun essai physique de0.5.0** : gestes, rendu, widget, TalkBack, fluidité/mémoire/batterie restent à vérifier sur téléphone. iOS : sources/prebuild seulement, aucun Xcode/IPA. Art et animations provisoires, aucun son, histoires/œufs, synchronisation ou publication boutique.

APK : **38 574 532 octets** ; SHA256 `85ed3972ce825bebafdd6751e3be45bc973fe749fc9eb9944bdf777bd18cff0f`. Rapport machine : `phase1-validation.json`. Le QR reste valide tant que le dépôt et ce chemin restent disponibles.

Code complet, instructions, décisions, backlog et rapport détaillé dans le dépôt privé `maxstg7-wq/refuge-vivant-game`, `docs/habitat-validation.md`. Ce dépôt public ne contient pas les sources privées. Assets originaux provisoires, licence de redistribution externe non accordée.
