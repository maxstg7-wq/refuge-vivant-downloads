# Refuge vivant — prototype Android 0.9.0

Compagnons fantastiques, soins tactiles, refuge personnel, invitations libres et relations persistantes. Aucun compte ni achat dans le jeu.

[Télécharger 0.9.0](https://raw.githubusercontent.com/maxstg7-wq/refuge-vivant-downloads/main/refuge-vivant-phase1-arm64.apk?v=0.9.0)

![QR du dernier APK](qr-android.png)

Le QR conserve sa cible historique `refuge-vivant-phase0-arm64.apk`, identique à l’alias phase1 : **0.9.0/code 11**. Le laboratoire original est archivé séparément ; ne pas réinstaller une ancienne version après migration.

## Installer

Android 7/API24 minimum, système **arm64-v8a**. Installer **par-dessus** Refuge vivant, sans désinstaller ni effacer ses données. Même identifiant `org.refugevivant.lab` et certificat de test. Les sauvegardes des mondes2/3/4/5 migrent vers6 ; SQLite reste3. Aucun compte GitHub requis pour télécharger cet APK autonome. Prévoir de l’espace libre pour le téléchargement et l’installation : Maxime a résolu le refus de 0.6.0 en libérant du stockage sur son téléphone.

## Cuisiner et découvrir les goûts

Toucher le **faitout dans le cocon**. Le petit livre montre les trois recettes gratuites. Glisser les ingrédients dans le bol, tourner dans le bol puis relâcher : un plat rejoint l’étagère. Le toucher des ingrédients est aussi possible. Vider le bol avant validation conserve le sac.

**Baies au miel** :1baie/1miel. **Bol des fleurs de lune** :2baies/1fleur. **Compote étoilée** :2baies/1poussière. Ce sont des coûts proposés pour les essais. Les ingrédients viennent gratuitement du jardin/de la cueillette.

Glisser un plat préparé vers le compagnon pour le servir. Toucher le compagnon change le destinataire parmi les individus présents. Les premières dégustations révèlent leurs goûts, conservés dans leur fiche et au carnet. Un favori n’accorde pas de bonus d’amitié ou d’installation. Les plats ne périment pas ; ils restent sur l’étagère après fermeture. Le service respecte sommeil, présence, satiété, délai et plafonds du repas ordinaire, sans consommer une seconde baie.

Les initiatives autonomes, l’abri à deux, les soins gestuels, la balle et les lucioles partagées, les cultures, l’atelier de parfum, les promenades et les relations persistantes sont conservés.

## Validation et limites

Voir [le rapport technique](phase1-validation.json). Tests du moteur et SQLite réels : 105 réussis ; 10 tests Kotlin du widget réussis. APK Release arm64 compilé, signature de test conservée et bundle Hermes comparé au build émulateur. Les contrôles natifs et leurs limites sont détaillés dans le rapport.

Les nouvelles scènes 0.9.0 restent à essayer sur téléphone physique. Visuels/animations originaux provisoires ; aucun son. Fluidité, consommation, grandes polices, TalkBack et rendu du widget sur le lanceur à mesurer. Widget natif conservé avec cartes/horloge/clignement discret selon lanceur et options ; aucune animation permanente promise en arrière-plan. iOS : sources uniquement, pas de compilation Mac ni test iPhone. Histoires/œufs, sauvegarde cloud/récupération utilisateur et boutique restent à la feuille de route. Aucun paiement, overlay ou publication boutique.

APK autonome : 39 059 328 octets. SHA256 : `1eff603cb8dd54e99962f4d2fb63a8ff7d8ee59dbf384bc7f4477cea569f2e54`.
