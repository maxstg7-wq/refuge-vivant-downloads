# Refuge vivant — prototype Android 0.2.0

Compagnons fantastiques et refuge personnel : soins, invitations libres, visiteurs récurrents et relations persistantes. Aucun compte dans le jeu, aucun achat.

[Télécharger le prototype interne 0.2.0](https://raw.githubusercontent.com/maxstg7-wq/refuge-vivant-downloads/main/refuge-vivant-phase1-arm64.apk?v=0.2.0)

![QR de téléchargement](qr-android.png)

Le QR conserve son adresse historique `refuge-vivant-phase0-arm64.apk`, maintenant mise à jour vers **0.2.0/code 4**. Les deux alias contiennent le même APK. Le laboratoire 0.0.1 est archivé séparément dans `refuge-vivant-phase0-archive.apk` ; ne pas le réinstaller sur une sauvegarde migrée.

## Installer et essayer

Sur Android arm64, Android 7 minimum, ouvrir l’APK et installer **par-dessus** Refuge vivant · labo. Ne pas désinstaller ni effacer les données. Même identifiant et certificat de test ; les sauvegardes précédentes sont conservées. Aucun compte GitHub requis pour le lien direct.

- Maison : glisse le bol, le bain, le lit ou la balle vers un compagnon. Le halo indique la cible ; relâcher dans le vide ne dépense rien. Tu peux aussi choisir le compagnon puis toucher l’objet, ou retoucher le compagnon pour une caresse.
- Jardin : touche les fleurs pour cueillir, balle/banc pour des moments à deux, panier pour l’atelier. Le panneau ramène à la maison. Les compagnons bougent et se rapprochent lors de leurs activités ; leurs préférences restent respectées.
- Atelier : glisse les ingrédients vers le flacon, ou touche-les. Le compteur montre ce qui est préparé. Touche Mélanger, puis Inviter sous un flacon prêt. Vider/quitter la préparation ne dépense rien ; seule la fabrication validée débite les ingrédients.
- Pour voir rapidement une visite : **Outils du prototype interne → +1 h**. +24 h teste les journées suivantes. Le temps simulé est sauvegardé, sans changer l’horloge du téléphone.

Trois décors dédiés originaux, mouvements individuels, effets après soin validé et indication des liens. Les visuels et animations restent provisoires : trois poses dessinées, translations et effets ; pas encore de son ou de séquence dessinée complète de chaque soin. Le second partenaire à trois présents est encore proposé automatiquement.

## Vérification

41 tests TypeScript/SQLite et six tests JVM du module Android réussis ; compilation native Release, bundle Hermes embarqué, signature v2, certificat inchangé, ABI arm64, aucune permission overlay/billing/stockage externe. **Cette version n’a pas encore été testée sur appareil** : gestes/défilement, TalkBack/grande police, widget, fluidité et batterie restent à observer. Retour utilisateur positif sur les versions précédentes, Android 10. iOS reporté, non compilé.

SHA256 : `0bcd3b27173239b559fe925a87af6f48bbe7e675e2d8112cd184d2d13898ead4` ; 37 762 458 octets. Résumé machine : `phase1-validation.json`. L’adresse du QR reste valide tant que le dépôt et ce chemin sont conservés ; l’hébergement n’est pas une garantie perpétuelle.

Sources complètes, instructions, décisions et rapport `docs/living-scene-validation.md` dans le dépôt séparé `maxstg7-wq/refuge-vivant-game`. Ce dépôt de téléchargement ne contient pas les sources privées. Assets originaux provisoires ; aucune licence publique de redistribution accordée. Aucune publication Google Play.
