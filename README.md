# Festival de l'Orientation — dix directions de look and feel

Galerie de maquettes pour l'application visiteur du Festival de l'Orientation
(APEL de Bussy-Saint-Georges, Ensemble scolaire Maurice Rondeau, 14 novembre 2026).

**En ligne :** https://festival-rondeau77.github.io/apel-festival-maquettes/

Dix directions visuelles, trois écrans chacune, dans un cadre de téléphone.
Les fonctions sont identiques partout ; ce qui change est la couleur, la
typographie, la hiérarchie et le premier écran. Les contenus affichés sont les
vraies données du classeur « Festival — Gestion » : neuf villages, deux étages,
sept événements, écoles confirmées.

## Ce dépôt

Site statique servi par GitHub Pages depuis `main` à la racine. Il n'y a rien à
construire : `git push` publie. `robots.txt` est en Disallow — les maquettes sont
publiques mais ne doivent pas être indexées.

| Fichier | Rôle |
|---|---|
| `index.html` | la galerie des dix directions |
| `01-…` à `10-…` | une page par direction |
| `apercus/` | captures PNG, pour partager sans ouvrir le site |

## Ce que ce n'est pas

Ce n'est pas le code de l'application. Les pages sont des images en HTML : rien
ne clique, les listes sont figées. L'application réelle vit dans le projet
`Festival_Orientation`.
