# N2L Labs - site statique GitHub Pages

Ce dossier contient une première version réellement publiable du site N2L Labs, sans serveur ni base de données.

## Projets affichés

- **N2L Studio Android** — logo fourni par toi
- **N2L Studio Lite** — logo fourni par toi
- **N2L Studio Translate** — logo fourni par toi, marqué **En développement**

L'application anti-gaspillage et le logiciel professionnel ne sont pas affichés pour le moment.

## Fichiers

- `index.html` : page d'accueil
- `projects/` : une page dédiée par application
- `assets/css/style.css` : design du site
- `assets/js/main.js` : menu mobile + année automatique
- `assets/img/` : logos
- `404.html` : page d'erreur GitHub Pages

## Publier gratuitement sur GitHub Pages

1. Crée un dépôt GitHub, par exemple `n2l-labs-site`.
2. Envoie tout le contenu de ce dossier à la racine du dépôt.
3. Dans GitHub : **Settings > Pages**.
4. Dans **Build and deployment**, choisis **Deploy from a branch**.
5. Sélectionne la branche `main` et le dossier `/ (root)`.
6. Enregistre. GitHub te donnera une adresse du type `https://tonpseudo.github.io/n2l-labs-site/`.

## Ajouter le domaine plus tard

Quand tu achèteras `n2l-labs.fr`, tu pourras le déclarer dans les paramètres GitHub Pages. Il n'est volontairement pas inclus ici pour éviter qu'un fichier `CNAME` bloque la publication avant que le domaine soit réellement configuré.

## Ajouter les téléchargements

Le plus simple sera d'utiliser **GitHub Releases** pour chaque application. Ensuite, remplace le texte temporaire de la section « Téléchargement » par un bouton vers la bonne release.

Exemple :

```html
<a class="btn btn-primary" href="URL_DE_LA_RELEASE">Télécharger</a>
```

## Important

Les textes sont volontairement modestes : ils indiquent que les projets sont développés en autodidacte, sur ton temps libre, sans te présenter comme une entreprise ou une équipe professionnelle.
