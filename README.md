# Clearart Maker by JukeBoX

Générateur de clearart (logos de films/séries sur fond transparent) en un seul fichier HTML, sans dépendance ni build. Recherche via l'API [TMDB](https://www.themoviedb.org/), puis export en PNG.

## Utilisation

Ouvrez [`index.html`](index.html) dans un navigateur, ou via GitHub Pages : https://VOTRE-USER.github.io/jukebox-clearart-maker/

Une clé API TMDB personnelle est requise (gratuite, à demander sur [themoviedb.org](https://www.themoviedb.org/settings/api)) et se configure directement dans l'interface. Elle est stockée uniquement dans le `localStorage` de votre navigateur, jamais transmise ailleurs.

## Fonctionnalités

- Recherche de films/séries par titre
- Sélection de clearart parmi les visuels disponibles sur TMDB
- Personnalisation (icône, texte, taille, marges)
- Export en PNG
