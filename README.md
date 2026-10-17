# Refuge vivant — prototype Android 0.6.0

Compagnons fantastiques, soins tactiles, refuge personnel, invitations libres et relations persistantes. Aucun compte ni achat dans le jeu.

[Télécharger 0.6.0](https://raw.githubusercontent.com/maxstg7-wq/refuge-vivant-downloads/main/refuge-vivant-phase1-arm64.apk?v=0.6.0)

![QR du dernier APK](qr-android.png)

Le QR conserve sa cible historique `refuge-vivant-phase0-arm64.apk`, identique à l’alias phase1 : **0.6.0/code 8**. Le laboratoire original est archivé séparément ; ne pas réinstaller une ancienne version après migration.

## Installer

Android 7/API24 minimum, système **arm64-v8a**. Installer **par-dessus** Refuge vivant, sans désinstaller ni effacer ses données. Même identifiant `org.refugevivant.lab` et certificat de test. Les sauvegardes des mondes2/3 migrent vers4 ; SQLite reste3. Aucun compte GitHub requis pour télécharger cet APK autonome.

## La nouvelle lisière

Dans le jardin, toucher **Vers les sentiers**, choisir un résident et un panneau, puis les trois petites traces pour accompagner son départ. Le sous-bois dure deux minutes simulées, le ruisseau cinq. Le compagnon garde son identité, sa place et ses liens ; son retour est garanti sans laisser le jeu ouvert.

Au retour, ouvrir son sac : une feuille de lune, une graine étoilée ou un galet nacré rejoint la collection, avec des ingrédients gratuits. Le sac n’expire pas. Une même trouvaille garde un seul emplacement dans l’album. Son résultat a été fixé et sauvegardé au départ : fermer le jeu ne relance pas le tirage.

Deux départs par journée du refuge, énergie minimale30/coût5, stimulation au retour+10 : paramètres proposés du prototype. Rentrer plus tôt ramène le résident sans trouvaille et conserve le départ dans le plafond du jour. Vacances suspend le temps et permet encore le rappel. Les visiteurs suivent leur propre promenade.

## Vivre au refuge

Maison/jardin/atelier/lisière se rejoignent par les objets du décor. Apporter trois bouchées, frotter les traces, caresser ou lancer la balle en gros plan ; une seule commande de soin est enregistrée à la fin. Les préférences, le repos et les plafonds sont respectés. Cultures sans expiration, créations placées durablement, parfum à préparer et à mélanger, visiteurs récurrents et accueil explicitement consenti.

Les intentions visibles suivent les besoins, la curiosité et l’activité réelle. Nouvelles planches de marche/reniflement, une seule balle entre deux amis ; aucun gain caché dans les déplacements. Les petits moments restent au carnet sans fenêtre automatique. Arrivées et grandes étapes relationnelles gardent leur mise en scène. Sac/carnet/options sont secondaires.

## Widget Android

Dans **⋯ → Ajouter le compagnon sur l’accueil** : décor jour/nuit, horloge, clignement discret, besoins enregistrés et nouvelles, notamment les promenades. Nouvelles change de carte ; Pause/Animer contrôle le mouvement ; Repas ouvre l’app sans dépense. Dernier état reçu seulement, sans second moteur. Actualisation demandée30min, différable par Android ; sommeil/mouvement réduit/économie imposent une image fixe et l’animation dépend du lanceur. Si ancien layout en cache, retirer seulement le widget et le rajouter.

## Vérifié et limites

**74 tests TypeScript/SQLite/présentation et dix tests Kotlin uniques réussis.** Release arm64 compilée, version/signature identiques à l’application attendue, bundle Hermes et53PNG référencés contrôlés ; même certificat que0.5.0. Aucun paiement, overlay, service permanent ou alarme exacte ajouté.

Sur émulateur natif Android10/API29 x86_64 : départ final en trois traces, fermeture forcée immédiatement, attente130s sans processus du jeu, réouverture avec résident revenu et sac prêt, collecte sauvegardée. La même feuille trouvée deux fois conserve un seul emplacement de collection. L’APK installé a été vérifié par empreinte et son bundle est strictement identique à celui du téléphone. Émulateur logiciel lent, animations système désactivées : aucune preuve de FPS/mémoire/batterie réels.

**Aucun essai physique de0.6.0** : gestes, taille/polices, TalkBack, widget/lanceur et performances restent à vérifier sur téléphone. Ruisseau/rappel et interactions restantes ne sont pas tous validés nativement. iOS : sources/prebuild seulement, aucun Xcode/IPA. Art et animations provisoires, sans véritables profils complets de marche ; aucun son, exploration à deux, histoires/œufs, synchronisation ou publication boutique.

APK : **38 891 020 octets** ; SHA256 `2d5c3bc98a8c7b30665fca296f210810d6cc37ab306d9cdad39c767316706617`. Rapport machine : `phase1-validation.json`. Le QR garde son adresse tant que le dépôt et ce chemin restent disponibles.

Code complet, compilation/lancement, décisions, backlog, manifeste d’assets et rapport détaillé : dépôt privé `maxstg7-wq/refuge-vivant-game`, `docs/exploration-validation.md`. Ce dépôt public ne contient pas les sources privées. Assets originaux provisoires ; licence de redistribution externe non accordée.
