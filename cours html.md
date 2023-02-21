

# Structuration d'une page HTML

## L'élément `<head>`:

Il contient des proprites essentielle de la page web
Chacune de ces proprietes est renseigné avec des elements enfants

## L'élément `<body>`:

Il contient le contenu de la page web


# Les différents types d'éléments:

## L'élément div :
L'élement `<div>` est un des conteneeurs les plus anciens du HTML. Il permet de creer une division structurel

## L'élément span :

L’élément `<span>` est souvent utilisé, par exemple, pour avoir une division au sein d’un paragraphe de texte. Ceci est très pratique pour mettre en forme de manière particulière du texte dans un texte formaté d’une autre manière.

## L'élément header :

L’élément `<header>` permet d’insérer une zone d’affichage pour les entêtes. Ces entêtes peuvent être utilisés à plusieurs endroits :

- au niveau de la page, c’est l'entête de page classique, souvent placé en haut de l’écran, avec un logo, un slogan, une barre de navigation principale...

## L'élément footer :

L’élément `<footer>` permet d’insérer une zone d’affichage pour les pieds de page. Nous retrouvons la même sémantique que pour les entêtes. Ces pieds de page peuvent être définis pour la page ou pour une autre zone d’affichage de celle ci, comme un article. Notez que l’usage d’un `<footer>` n’implique pas forcément l’usage d’un `<header>`.

## L'élément nav:

L’élément `<nav>` , comme son nom le laisse supposer, est dédié à l’affichage d’une barre de navigation avec des liens hypertextes. Mais attention, ne vous sentez pas obligé de n’avoir qu’une seule zone de navigation par page. On ne peut pas créer autant d’éléments `<nav>` que vous avez de navigations différentes dans vos pages, à partir du moment où chacun d’entre eux est bien identifié. L’élément `<nav>` est plutôt dédié à la navigation principale du site, à la création de liens entre les pages du site. Vous pouvez inclure une navigation principale `<nav>` dans un entête `<header>` et une navigation secondaire `<nav>` dans un pied de page `<footer>`, par exemple.

## L'élément main:

L’élément `<main>` permet d’indiquer le contenu principal de la page. Ce contenu doit être unique et ne pas être répété dans la page. De plus, le W3C indique précisément son contexte d’utilisation : il ne doit pas être utilisé à l’intérieur, comme élément inclus, dans les éléments `<article>`, `<aside>`, `<footer>`, `<header>` ou `<nav>`.

## L'élément section:

L’élément `<section>`

Permet de regrouper des éléments partageant une même thématique. Cela permet de regrouper dans un même élément un contenu structuré, avec son entête et son pied de page. L’utilisation de plusieurs éléments
distinguera plusieurs parties, plusieurs sections au sein d’une même page, avec d’autres éléments de structure imbriqués.


# Les balises HTML

Un element html est composé d'une balise d'ouverture et de fermeture:

```html
<p>contenu</p>
```

Certaines balises n'ont pas de fermeture :

```html
<hr> (sert à créer une ligne)
```

Chaque elements HTML peut avoir un ou plusieurs attributs:

```html
<p id="test"> ceci est un paragraphe</p>
```

Pour inserer une image il faut taper:
```html
<img src="source de l'image"alt="image not found" title="titre de l'image">
```
L'attribut `<alt>` sert à afficher un texte de remplacement en cas d'erreur 


il est important de respecter la hierarchi et l'ordre des `<H1>` `<H2>` etc...