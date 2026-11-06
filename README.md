# sae5-game

Jeu de société développé avec Unity, dans le cadre de la SAÉ 5.

## Prérequis

- Unity (version à préciser dès le démarrage du projet, tout le monde doit utiliser la même)
- [Git LFS](https://git-lfs.com) : `git lfs install` avant le premier clone

## Installation

1. Installer [Git](https://git-scm.com) et [Git LFS](https://git-lfs.com), puis activer LFS une seule fois :
   ```bash
   git lfs install
   ```
2. Installer [Unity Hub](https://unity.com/download) puis, depuis le Hub, la version d'Unity du projet (indiquée dans `ProjectSettings/ProjectVersion.txt` une fois le projet créé).
3. Cloner le dépôt :
   ```bash
   git clone https://github.com/leolesimple/sae5-game.git
   cd sae5-game
   ```
4. Dans Unity Hub : **Add > Add project from disk**, sélectionner le dossier `sae5-game`, puis l'ouvrir. Le premier import des assets peut prendre plusieurs minutes.
5. Vérifier les réglages ci-dessous.

## Réglages Unity obligatoires

Dans `Edit > Project Settings > Editor` :

- **Version Control > Mode** : `Visible Meta Files`
- **Asset Serialization > Mode** : `Force Text`

## Contribuer

Voir [CONTRIBUTING.md](CONTRIBUTING.md).

## Licence

[MIT](LICENSE)
