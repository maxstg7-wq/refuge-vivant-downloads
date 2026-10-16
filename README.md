# Refuge vivant — prototype Android 0.4.0

Compagnons fantastiques, soins, refuge personnel, invitations libres et relations persistantes. Pas de compte dans le jeu, aucun achat.

[Télécharger 0.4.0](https://raw.githubusercontent.com/maxstg7-wq/refuge-vivant-downloads/main/refuge-vivant-phase1-arm64.apk?v=0.4.0)

![QR du dernier APK](qr-android.png)

Le QR conserve sa cible historique `refuge-vivant-phase0-arm64.apk`, identique à l’alias phase1 : **0.4.0/code 6**. L’ancien laboratoire est archivé séparément et ne doit pas être réinstallé après migration.

## Installer

Android arm64, Android 7 minimum. Installer **par-dessus** Refuge vivant · labo, sans désinstaller ni effacer ses données. Identifiant et signature de test conservés. Le monde migre 2→3 sans perdre les noms, l’inventaire, les amitiés, les horloges et les reçus. Ne pas réinstaller une ancienne version après migration.

## Dans le refuge

- Soins : glisser bol, bain, lit ou balle vers un compagnon, ou le choisir puis toucher l’objet. Déposer dans le vide ne dépense rien. Dessins de repas/bain/câlin/jeu et refus respectant préférences et repos.
- Jardin : toucher une terre pour planter gratuitement, une pousse pour arroser une fois, puis Récolter lorsqu’elle est prête. Trois cultures, sans expiration. Les fleurs sauvages donnent aussi des ressources gratuites.
- Maison : toucher **Aménager**, puis un plan pour créer une jardinière, une lanterne ou un tapis ; glisser ensuite la création. Coût unique et place sauvegardée. Terminer revient aux soins.
- Rencontres : sélectionner un compagnon puis glisser balle/banc vers un autre pour choisir les deux participants. Atelier : préparer les ingrédients et le parfum, puis Inviter ; les visiteurs restent libres.
- Le fil du refuge relie ces découvertes et reprend les accomplissements conservés. Les outils internes +1 h/+24 h permettent des essais accélérés, distincts du temps réel.

## Le widget Android

Toucher **✧ Widget** dans l’application pour l’ajouter. Décor jour/nuit, horloge du téléphone, clignement natif, besoins enregistrés et nouvelles du refuge. **Nouvelles** parcourt besoins/compteurs/événement sans ouvrir le jeu ; **Pause/Animer** contrôle le mouvement ; **Repas** ouvre le bon compagnon sans dépenser de baie.

Le sommeil, l’économie d’énergie et la suppression des animations imposent une image fixe. Les valeurs sont celles du dernier état reçu, sans deuxième moteur ; les états anciens sont signalés. Actualisation système demandée à 30 minutes, différable par Android. L’animation dépend du lanceur et n’est pas une présence flottante. Si l’ancien layout reste en cache, retirer uniquement le widget et l’ajouter à nouveau ; ne pas désinstaller l’app.

## Vérifié et restant à tester

53 tests TypeScript/SQLite/présentation et dix tests uniques du module Android réussis. Compilation native Release, signature v2 identique, ABI arm64, ressources ViewFlipper/TextClock et dessins embarqués contrôlés. Aucun overlay, paiement, service permanent ou alarme exacte.

**Aucun appareil n’a exécuté 0.4.0 dans le cloud.** Il reste à vérifier le lanceur réel, affichage/clignement/boutons/redimensionnement du widget, gestes, accessibilité, fluidité, mémoire et batterie. iOS conserve son widget précédent, source/prebuild seulement, non compilé. Art provisoire, sans sons, collisions de placement, histoires/œufs ou publication boutique.

APK : 38 566 584 octets ; SHA256 `3867ae138e703911db4c32d7523ae577a22608ceccd647f8c29c3ce52cd8ee93`. Rapport machine : `phase1-validation.json`. Le QR reste valide tant que ce dépôt et son chemin sont conservés.

Sources privées, instructions, décisions et rapport complet : dépôt séparé `maxstg7-wq/refuge-vivant-game`, `docs/refuge-widget-validation.md`. Ce dépôt public ne contient pas les sources privées. Assets originaux provisoires, licence de redistribution externe non accordée.
