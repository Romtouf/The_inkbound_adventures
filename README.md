<img width="1920" height="1080" alt="niveau" src="https://github.com/user-attachments/assets/90c548cd-b95c-4ff8-84c4-c6a24c9edf2c" />
# The Inkbound Adventures — Démo

Jeu de plateforme 2D en noir et blanc, dans le style des dessins animés américains
des années 1930 : personnages « rubber hose », grain de pellicule, jazz de cabaret.

Le héros, **Nib**, est une goutte d'encre vivante. Il part réunir les fragments du
Grand Projecteur, brisé par l'Encre Noire qui recouvre le monde d'Inkoria.

## Télécharger

| Plateforme | Fichier | Configuration |
|---|---|---|
| **Windows** | [InkboundAdventures-Demo.exe](https://github.com/Romtouf/The_inkbound_adventures/releases/latest) (114 Mo) | Windows 10 / 11, 64 bits |
| **Android** | [InkboundAdventures-Demo.apk](https://github.com/Romtouf/The_inkbound_adventures/releases/latest) (57 Mo) | Android 7.0 ou plus récent |

**Windows** : lancer le fichier `.exe`, sans installation. Windows peut afficher
« Windows a protégé votre ordinateur » parce que le fichier n'est pas signé :
cliquer sur *Informations complémentaires*, puis *Exécuter quand même*.

**Android** : ouvrir le fichier `.apk` sur le téléphone et autoriser l'installation
depuis cette source quand Android le demande.

## Contenu de la démo

La démo contient **le premier monde complet**, la Prairie des Croquis :

- la cinématique d'introduction ;
- 4 niveaux : *Le Réveil d'Inkoria*, *Les Collines de Papier*, *Le Moulin Grinçant*
  et *Le Terrier des Encriers* ;
- le combat contre **le Sanglier à l'Encre**, qui fait gagner le double saut ;
- dans chaque niveau, des objets à trouver : 3 étoiles d'encre, une page secrète et des pièces.

Le jeu complet compte 10 mondes, 40 niveaux, 10 boss et 32 ennemis.

## Commandes

| Action | Clavier | Manette |
|---|---|---|
| Se déplacer | ← → ou Q / D | stick / croix |
| Sauter (maintenir = plus haut) | Espace | A |
| Courir | Maj | B |
| Coup de gant | J | X |
| Glissade | Bas en courant | Bas en courant |
| Actionner un levier | Haut | Haut |
| Pause | Échap | Start |
| Plein écran / fenêtre | F11 | — |

Sur Android, les commandes tactiles apparaissent à l'écran. Pour se déplacer, on
choisit entre un joystick et des flèches. Les touches se reconfigurent dans
*Options → Commandes*.

## Options

- Français et anglais
- 3 difficultés et 3 emplacements de sauvegarde
- Mode assistance : vies infinies, jeu ralenti à 85 % ou 70 %, course automatique

## Fabrication

- **Moteur** : Godot 4.7, GDScript
- **Graphismes** : tout est dessiné en code, à part les icônes. Il n'y a aucune image
  de personnage ou de décor : Nib, les ennemis, les boss et les décors sont tracés
  à la volée, ce qui donne l'animation « rubber hose ».
- **Musique et bruitages** : 14 musiques et 82 bruitages originaux, synthétisés par
  un script Python (piano stride, contrebasse, trombone « wah-wah », filtre gramophone).
- **Niveaux** : écrits sous forme de grilles de texte. Un outil vérifie
  automatiquement que la sortie, les étoiles, la page secrète et le boss de chaque
  niveau sont atteignables.
- **Sensations de jeu** : mouvements fluides même sur les écrans à 120 / 144 Hz,
  micro-pause à l'impact, zoom pendant les combats de boss.

## Crédits

Conception, programmation, graphismes et musique : **[Codebyr]** — [codebyr.dev]

Polices *Limelight* et *Fredoka* : SIL Open Font License.
Démo distribuée gratuitement pour présenter le projet. Tous droits réservés.
