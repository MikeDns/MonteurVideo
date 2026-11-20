# Monteur Vidéo

Extraire des passages de plusieurs vidéos et les assembler en une seule vidéo, sur Windows, en local.

- Plusieurs passages par vidéo, ordre libre, GIF et cartons noir / blanc / fondu entre les passages
- Aperçu vidéo, forme d'onde, marquage au clavier (I / O)
- Export accéléré par le processeur graphique quand il est disponible (Intel Quick Sync, NVIDIA, AMD), sinon par le processeur
- S'adapte à la machine : économe sur un PC modeste, plus rapide sur un PC puissant

## Installation

1. Téléchargez `MonteurVideo-Setup-x.y.z.exe` dans la [dernière version](https://github.com/MikeDns/MonteurVideo/releases/latest).
2. Lancez-le : aucun droit administrateur n'est nécessaire.
3. Au premier lancement, Monteur Vidéo prépare Python et ses composants vidéo (une seule fois, quelques minutes, connexion internet nécessaire).

Windows 10 ou 11, 64 bits. Les mises à jour sont proposées dans l'application, avec retour possible à la version précédente.

## Licence

GPL-3.0. Le code de l'application est livré lisible dans le dossier d'installation (`versions\x.y.z`).
Composants tiers : FFmpeg (build gyan.dev), libmpv (build shinchiro), Qt / PySide6 (LGPL).
