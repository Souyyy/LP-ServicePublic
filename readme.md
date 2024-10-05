# README.md

## Présentation du projet

Le DM vise à développer une page web responsive pour le tableau de bord du service public. Cette page doit être élaborée à partir de deux images : une version pour ordinateur et une autre pour téléphone afin de garantir une page responsive. Le point de départ sera un fichier HTML contenant les éléments de base du code. La conception de la page doit utiliser le framework Bootstrap pour faciliter la mise en page, la structure de la page inclura une barre de navigation, une section principale, une colonne latérale et un pied de page. 

## Démarche du développement

### 1. Structure Sémantique
Le fichier d'origine a été conservé tel quel, sans ajout de nouvelles balises. La seule modification effectuée a été l'ajout de classes CSS à certaines balises pour améliorer le style et la mise en page. Ainsi la page HTML est composé d'un `<header>`, d'un `<main>`, d'un `<aside>` et d'un `<footer>`

- **Header** : Le `<header>` contient le logo et le formulaire de recherche, ainsi que la barre de navigation.
- **Main** : La balise `<main>` contient les articles principaux.
- **Aside** : Utilisée pour la barre latérale, la balise `<aside>` contient des liens supplémentaires et des informations.
- **Footer** : La section `<footer>` contient les informations légales, les contacts, et les droits d'auteur.

### 2. Ajout du Framework Bootstrap
J'ai intégré le **framework Bootstrap** dans son intégralité pour optimiser la mise en page et la réactivité de notre site web, bien que toutes ses fonctionnalités n'aient pas été nécessaires. Voici les principaux éléments que j'ai effectivement utilisés :

- Ajout du **framework Bootstrap** via un **CDN** pour une utilisation complète.
- Utilisation des classes `nav`, `row` et `col` pour la mise en page.
- Application des classes pour les **marges** et **paddings** (ex. `pt`, `pb`, `mt`, `ml` , `m-auto`, `...`).
- Utilisation des **breakpoints** (`sm`, `md`, `lg`) pour assurer la responsivité.
- **Menu de navigation** : Les menus de navigation sont intégrés dans des `ul.nav` avec des colonnes Bootstrap (`col-md-3`) pour s'assurer qu'ils s'alignent sur les colonnes principales (`<main>` et `<aside>`).
- **Pagination** : Les éléments dans la section principale et la colonne latérale sont paginés en utilisant des classes comme `row-cols-1` et `row-cols-md-3`, ce qui permet d'avoir trois articles dans une ligne sur un écran large, et un seul article sur les petits écrans.

### 3. Ajout du CSS

Pour la mise en forme et la personnalisation de ce site, j'ai développé un **fichier CSS dédié**, en adoptant une approche **mobile-first** avant d'étendre les styles pour les écrans d'ordinateur. Voici les principaux éléments que j'ai ajouté:

- J'ai intégré mon fichier CSS, situé dans le dossier `/css/style.css`, pour appliquer des **styles personnalisés**.
- **Gestion du header** : Le header a été entièrement stylisé en CSS, notamment pour assurer l'affichage dynamique du sous-menu lors du survol de l'utilisateur.
- J'ai défini des **styles spécifiques** pour les éléments de la page, les textes, y compris la taille, la police, et les couleurs...
- **Flexbox** : Utilisé pour aligner les éléments dans le `footer` et pour le menu déroulant, ce qui garantit un alignement correct et une meilleure gestion de l'espace.
- Utilisation de **Media queries** pour adapter le design aux écran de tablette/d'ordinateur, par exemple avec `@media only screen and (min-width: 768px)` pour ajuster les styles à partir de cette largeur.

## Lien vers la production

Vous pouvez visualiser le projet à l'adresse suivante : [https://github.com/Souyyy/LP-ServicePublic](https://github.com/Souyyy/LP-ServicePublic)