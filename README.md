# Savoir Réagir – projet Android

Application de premiers secours 100 % hors ligne (aucune permission, aucun accès réseau).
Le contenu se trouve dans `app/src/main/assets/index.html`.

## Obtenir l'APK (méthode la plus simple)

1. Installez **Android Studio** (gratuit) : https://developer.android.com/studio
2. `File > Open` et choisissez le dossier `SavoirReagir`.
3. Laissez la synchronisation Gradle se terminer (téléchargement automatique du SDK si besoin).
4. Menu `Build > Build Bundle(s) / APK(s) > Build APK(s)`.
5. L'APK est dans `app/build/outputs/apk/debug/app-debug.apk`. Copiez-le sur le téléphone et ouvrez-le
   (autorisez l'installation depuis cette source).

Pour tester directement : branchez le téléphone (débogage USB activé) et cliquez sur ▶ Run.

## Modifier le contenu

Éditez `app/src/main/assets/index.html` (fiches, textes, illustrations), puis recompilez.

## Publier sur le Google Play Store

Générez un bundle signé (`Build > Generate Signed Bundle / APK > Android App Bundle`).
Un compte développeur Google Play est nécessaire. Pour une application de santé, faites relire
le contenu par un professionnel du secourisme avant publication.

## À propos

La page « À propos » (logo en haut, sous le nom) est dans `index.html` : fonction `openAbout()`. Le logo est intégré en base64 dans la page.

