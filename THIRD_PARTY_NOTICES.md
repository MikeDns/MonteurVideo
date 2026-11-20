# Composants tiers

Cut Together est un logiciel gratuit, © 2026 Mike DANSOU, tous droits réservés ([conditions d'utilisation](LICENSE)).
Il s'appuie sur les composants suivants, qui restent sous leur propre licence.

## Inclus dans l'installateur

| Composant | Licence | Source |
|---|---|---|
| uv (Astral) | MIT ou Apache-2.0 | <https://github.com/astral-sh/uv> |

## Installés au premier lancement (dépendances Python)

| Composant | Licence | Source |
|---|---|---|
| Python 3.11 | PSF License | <https://www.python.org> |
| Qt for Python (PySide6), Shiboken | LGPL-3.0 | <https://www.qt.io/qt-for-python> |
| python-mpv | LGPL-2.1 ou ultérieure | <https://github.com/jaseg/python-mpv> |
| truststore | MIT | <https://github.com/sethmlarson/truststore> |

La liste complète et figée des dépendances est dans `uv.lock`.

## Composants vidéo (téléchargés au premier lancement)

Ce sont des programmes et bibliothèques séparés, utilisés tels quels, sans modification.

| Composant | Licence | Source |
|---|---|---|
| FFmpeg, ffprobe (build gyan.dev) | GPL-3.0 | <https://www.gyan.dev/ffmpeg/builds/> · code : <https://github.com/FFmpeg/FFmpeg> |
| libmpv | voir le fichier SOURCES.txt fourni avec | <https://mpv.io> · code : <https://github.com/mpv-player/mpv> |

Les textes de licence et l'adresse exacte du code source de chaque composant sont fournis dans le dossier
`bin` de l'installation (`LICENSE-ffmpeg.txt`, `SOURCES.txt`).
