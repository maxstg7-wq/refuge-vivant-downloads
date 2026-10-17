# Refuge vivant — prototype Android 0.8.0

Compagnons fantastiques, soins tactiles, refuge personnel, invitations libres et relations persistantes. Aucun compte ni achat dans le jeu.

[Télécharger 0.8.0](https://raw.githubusercontent.com/maxstg7-wq/refuge-vivant-downloads/main/refuge-vivant-phase1-arm64.apk?v=0.8.0)

![QR du dernier APK](qr-android.png)

Le QR conserve sa cible historique `refuge-vivant-phase0-arm64.apk`, identique à l’alias phase1 : **0.8.0/code 10**. Le laboratoire original est archivé séparément ; ne pas réinstaller une ancienne version après migration.

## Installer

Android 7/API24 minimum, système **arm64-v8a**. Installer **par-dessus** Refuge vivant, sans désinstaller ni effacer ses données. Même identifiant `org.refugevivant.lab` et certificat de test. Les sauvegardes des mondes2/3/4 migrent vers5 ; SQLite reste3. Aucun compte GitHub requis pour télécharger cet APK autonome. Prévoir de l’espace libre pour le téléchargement et l’installation : Maxime a résolu le refus de 0.6.0 en libérant du stockage sur son téléphone.

## Deux nouvelles étapes

**Petites initiatives autonomes.** Observer le jardin et le cocon : les compagnons jouent, observent, font une petite toilette, grignotent ou se reposent selon leur état. Un résident peut arroser une pousse. Toucher la pastille de son nom permet de le retrouver dans l’autre pièce. Les gains sont modestes et plafonnés ; le sac n’est jamais vidé par ces initiatives.

**Un abri à construire à deux.** Toucher le plan de feuilles du jardin. Deux compagnons qui se connaissent peuvent poser successivement les fleurs, le miel puis la poussière d’étoile en les glissant vers le cercle. Si nécessaire, partager d’abord un moment calme au banc. Chaque pièce est sauvegardée immédiatement. Si un visiteur repart, le chantier garde ses deux bâtisseurs et attend leur retour. Toucher l’abri terminé propose un repos commun ; toucher le nom d’un dormeur le réveille doucement.

Les coûts et rythmes sont des propositions du prototype. Ce petit aménagement gratuit conserve les règles d’accueil et les relations ; les histoires exceptionnelles et les œufs restent à venir. Les soins gestuels, la balle et les lucioles à deux, les cultures, l’atelier, les promenades et le carnet des versions précédentes sont conservés.

## Validation et limites

Voir [le rapport technique](phase1-validation.json). Tests du moteur et SQLite réels : 96 réussis ; 10 tests Kotlin du widget réussis. APK Release arm64 compilé, signature de test conservée et bundle Hermes comparé au build émulateur. Les contrôles natifs et leurs limites sont détaillés dans le rapport.

Les nouvelles scènes 0.8.0 restent à essayer sur téléphone physique. Visuels/animations originaux provisoires ; aucun son. Fluidité, consommation, grandes polices, TalkBack et rendu du widget sur le lanceur à mesurer. Widget natif conservé avec cartes/horloge/clignement discret selon lanceur et options ; aucune animation permanente promise en arrière-plan. iOS : sources uniquement, pas de compilation Mac ni test iPhone. Histoires/œufs, sauvegarde cloud/récupération utilisateur et boutique restent à la feuille de route. Aucun paiement, overlay ou publication boutique.

APK autonome : 38 962 960 octets. SHA256 : `a505f552d1646bd0956c8ef8a4e6eabfb76401605801b5566b3304226c15e919`.
