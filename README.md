# Refuge vivant — prototype Android 0.7.0

Compagnons fantastiques, soins tactiles, refuge personnel, invitations libres et relations persistantes. Aucun compte ni achat dans le jeu.

[Télécharger 0.7.0](https://raw.githubusercontent.com/maxstg7-wq/refuge-vivant-downloads/main/refuge-vivant-phase1-arm64.apk?v=0.7.0)

![QR du dernier APK](qr-android.png)

Le QR conserve sa cible historique `refuge-vivant-phase0-arm64.apk`, identique à l’alias phase1 : **0.7.0/code 9**. Le laboratoire original est archivé séparément ; ne pas réinstaller une ancienne version après migration.

## Installer

Android 7/API24 minimum, système **arm64-v8a**. Installer **par-dessus** Refuge vivant, sans désinstaller ni effacer ses données. Même identifiant `org.refugevivant.lab` et certificat de test. Les sauvegardes des mondes2/3 migrent vers4 ; SQLite reste3. Aucun compte GitHub requis pour télécharger cet APK autonome. Prévoir de l’espace libre pour le téléchargement et l’installation : Maxime a résolu le refus de 0.6.0 en libérant du stockage sur son téléphone.

## Jouer ensemble dans la clairière

Sélectionner un compagnon puis déposer la balle ou le banc sur un autre ; un toucher simple garde un partenaire par défaut. La balle se glisse entre les deux amis en quatre passes alternées. Au banc, guider trois lucioles dans le cercle entre eux. Aucun chronomètre ni perte sur un geste manqué. Une assistance lecteur d’écran est prévue.

Lune peut préférer le calme à la première rencontre. Sommeil, fatigue, présence et réservations restent prioritaires. La progression du lien est sauvegardée seulement après la scène terminée, avec les plafonds et l’espacement existants. Une partie interrompue ne crée pas de souvenir. Une erreur de sauvegarde permet de réessayer avec le même identifiant. Les liens et souvenirs restent au carnet.

Maison, soins tactiles, jardin cultivable, atelier de parfum, aménagement et promenades de 0.6.0 sont conservés : le panneau du jardin mène à la lisière, trois traces accompagnent un départ, le résident revient avec un sac sans expiration et une collection persistante. Aucun habitant ne disparaît à cause d’une absence.

## Validation et limites

Voir [le rapport technique](phase1-validation.json). Tests du moteur et SQLite réels : 84 réussis ; 10 tests Kotlin du widget réussis. APK Release arm64 compilé, signature de test conservée et bundle Hermes comparé au build émulateur. Les contrôles natifs et leurs limites sont détaillés dans le rapport.

Les nouvelles scènes 0.7.0 restent à essayer sur téléphone physique. Visuels/animations originaux provisoires ; aucun son. Fluidité, consommation, grandes polices, TalkBack et rendu du widget sur le lanceur à mesurer. Widget natif conservé avec cartes/horloge/clignement discret selon lanceur et options ; aucune animation permanente promise en arrière-plan. iOS : sources uniquement, pas de compilation Mac ni test iPhone. Histoires/œufs, sauvegarde cloud/récupération utilisateur et boutique restent à la feuille de route. Aucun paiement, overlay ou publication boutique.

APK autonome : 38 904 332 octets. SHA256 : `4ac0663f4e812ea6130d5b6c0ddc3a85a50f8b84aca766ba49aee917b1f757e0`.
