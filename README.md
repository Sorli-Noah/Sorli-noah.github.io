# Portfolio – Noah Sorli

Site statique : `index.html` et `style.css`. Pas de dépendance, pas de build.

## Structure

```
index.html
style.css
CV_Noah_Sorli.pdf
img/          portrait.jpg et images des projets
```

## Images

Le portrait de l’accueil est `img/portrait.jpg` (carré, 800 × 800 conseillé).

Déposer les images dans `img/`, puis indiquer le chemin dans l’attribut `style` du lien du projet :

```html
<a href="…" style="--img: url('img/mon-image.jpg')">
```

Sans image, un fond dégradé s’affiche. Format conseillé : JPG, 1920 × 1080, moins de 400 Ko.

## CV

Les boutons « Télécharger le CV » pointent vers `CV_Noah_Sorli.pdf`, à placer à côté de `index.html`.

## Liens vidéo

Chaque projet est un lien : remplacer la valeur de `href` par l’adresse de la vidéo. Un lien YouTube « non répertorié » convient pour une vidéo qui ne doit pas être publique.

## Ajouter un projet

Copier un bloc `<article class="project">` dans `<div class="project-list">`, puis modifier le titre, les textes, le lien et l’image. L’ordre dans le fichier est l’ordre d’affichage. Le panneau de texte alterne automatiquement entre la gauche et la droite.

## Couleurs et polices

Les variables sont regroupées en tête de `style.css`, dans `:root`.

## Mise en ligne (GitHub Pages)

1. Créer un dépôt public nommé `noah-sorli.github.io` (nom du compte GitHub suivi de `.github.io`).
2. Y déposer `index.html`, `style.css`, `CV_Noah_Sorli.pdf` et le dossier `img`.
3. Dans Settings > Pages, choisir la branche `main` et le dossier `/ (root)`.

Le site est alors disponible à l’adresse `https://noah-sorli.github.io`.
