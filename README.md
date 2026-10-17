# ScratchCode pour Android

Application Android de **[ScratchCode](https://scratchcode.web.app)** : Scratch 3 où les blocs s'écrivent en code texte, avec autocomplétion, extensions TurboWarp, exemples de jeux et manette tactile.

## Télécharger

➡️ **[ScratchCode.apk](https://github.com/haydarcreator/scratchcode-android/releases/latest/download/ScratchCode.apk)** (dernière version)

Ou toutes les versions dans l'onglet [Releases](https://github.com/haydarcreator/scratchcode-android/releases).

## Installer

1. Télécharge le fichier `ScratchCode.apk` sur ton téléphone.
2. Ouvre-le et autorise l'installation depuis ton navigateur si Android le demande.
3. Lance **ScratchCode** depuis l'écran d'accueil.

Il faut Android 7.0 ou plus récent et Google Chrome installé.

## Comment c'est fait

L'application est une *Trusted Web Activity* générée avec [Bubblewrap](https://github.com/GoogleChromeLabs/bubblewrap) : elle ouvre `scratchcode.web.app` en plein écran via Chrome, avec la même connexion (Google, Microsoft, e-mail) et les mêmes projets que sur le web. Les mises à jour du site arrivent automatiquement dans l'appli.

- Paquet : `app.web.scratchcode.twa`
- Empreinte SHA-256 du certificat : `90:00:EE:BB:04:CD:AE:58:A8:F1:99:31:A8:1D:DD:A6:67:A3:15:02:4F:41:C5:03:1D:F9:A1:7F:42:CA:46:A2`
