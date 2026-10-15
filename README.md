# Refuge vivant — prototype Android 0.1.0

Compagnons fantastiques et refuge personnel : soins, invitations libres, visiteurs récurrents et relations persistantes. Ce prototype n’a aucun achat.

[Télécharger le prototype interne 0.1.0](https://raw.githubusercontent.com/maxstg7-wq/refuge-vivant-downloads/main/refuge-vivant-phase1-arm64.apk)

![QR de téléchargement](qr-android.png)

Le QR conserve son adresse historique `refuge-vivant-phase0-arm64.apk`, maintenant mise à jour vers **0.1.0/code 2**. Le laboratoire 0.0.1 est archivé séparément dans `refuge-vivant-phase0-archive.apk` ; ne pas le réinstaller sur une sauvegarde migrée.

## Installer la mise à jour

Ouvrir l’APK sur Android arm64, Android 7 minimum. Installer **par-dessus** Refuge vivant · labo sans désinstaller ni effacer ses données. Le certificat de test est identique au build initial. La migration conserve Véli et les données du labo, puis crée le monde jouable. Aucun compte GitHub requis pour le lien direct. Ne pas désactiver Play Protect ; conserver tout avertissement pour diagnostic.

Maison : cinq soins et choix du résident pour le widget. Jardin : cueillette gratuite, visiteurs, moments à deux et offres de résidence. Atelier : fabriquer puis poser une invitation. Carnet : rencontres et souvenirs. Pour une première démonstration rapide, ouvrir **Outils du prototype interne → +1 h**. +24 h permet de tester les journées suivantes. Les animaux restent libres et l’installation demande un accord explicite.

Ce build interne inclut les outils de temps, désactivés dans un build normal. Nouveaux textes FR, visuels/animations simples provisoires, aucune boutique ni publication Google Play. Le retour utilisateur du labo est positif ; le nouveau build reste à tester sur appareil. iOS est reporté.

Vérifié : 36 tests TypeScript/SQLite, six tests Android, compilation native Release, signature v2, même certificat, ABI arm64, permissions sans overlay/billing. SHA256 : `43ec6f213178b485f584e9ba452e6c90c6cf5c1460837ed11b31cd0ba3569af0`. Résumé machine : `phase1-validation.json`. Le téléchargement reste disponible tant que le dépôt et le fichier sont conservés.

Sources complètes, instructions et rapports dans le dépôt séparé `maxstg7-wq/refuge-vivant-game`. Ce dépôt de téléchargement ne contient pas les sources privées. Assets originaux provisoires ; aucune licence publique de redistribution accordée.
