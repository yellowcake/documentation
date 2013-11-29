# ![image](./images/yellowcake.png) [DOCS](./) : Front-end Code Standards

> * **Date :** 2013
* **Auteur :** David COLIN, front-end developer @[Yellowcake](http://www.yellowcake.net)
* **Public visé :** Intégrateurs, développeurs
* **Inspiré par :** [Google Style Guide](http://google-styleguide.googlecode.com/svn/trunk/htmlcssguide.xml)

> Ce document contient les règles de codage et les bonnes pratiques adoptées par l'agence Yellowcake pour l'intégration et le développement d'applications web. Son but est l'uniformisation du code et l'amélioration du travail collaboratif.


# ![image](./images/html5-performance.png) Pratiques générales

## Encodage

L'UTF-8 (sans BOM) est préféré pour tous les documents, vérifiez que votre éditeur de code soit bien configuré ainsi.

## Indentation et espaces

Utilisez 2 espaces pour indenter votre code. Pas de tablulation. Supprimez les espaces en fin de ligne, ils sont inutiles et peuvent générer des différences entre les versions de fichiers avec GIT.

```
h1 {
  font-size: 22px;
}
```

## Casse

Utilisez uniquement les minuscules. Cette règle s'applique aux balises HTML, attributs, valeurs des attributs, sélecteurs CSS, propriétés et valeurs de propriété.

Non recommandé :

```
<A HREF="/">Accueil</A>
```

**Recommandé :**

```
<img src="yellowcake.png" alt="Yellowcake">
```

Non recommandé :

```
color: #FECC00;
```

**Recommandé :**

```
color: #fecc00;
```
## Commentaires

Prenez le temps de commenter votre code lorsque vous estimez qu'il mérite une explication particulière. Pensez aux autres personnes qui vont reprendre votre code ou tout simplement à vous même, car l'autre c'est vous dans 6 mois !

N'hésitez pas à marquer avec le tag `TODO` les portions du code pour lesquelles vous n'avez pas terminé le travail :

```
/* TODO: prévoir un effet de survol sur les liens */
a {
  text-decoration: none;
} 
```

* * *

# ![image](./images/html5-markup.png) HTML

## Doctype

La syntaxe HTML5 est préférée pour tous les documents HTML.

```
<!DOCTYPE html>
```
## Encodage

Tout document HTML5 devra comporter la meta suivante :

```
<meta charset="utf-8">
```
## Validation du code

Produisez un code HTML valide. Pour vérifier votre code, utilisez le [validateur HTML du W3C](http://validator.w3.org/nu).

## Sémantique

Donnez du sens à votre markup HTML en utilisant les balises appropriées :

* Utilisez les niveaux de titre `<h1> à <h6>` pour structurer l'information
* Utilisez la balise `<p>`pour entourer un paragraphe et la balise `<br />` pour un  retour chariot unique
* N'utilisez surtout pas les `<table>` pour votre mise en page, les tableaux c'est fait pour afficher des données tabulaires !
* Utilisez les `<header> <section> <article> <aside> <div>` pour structurer votre page
* Utilisez la balise `<a>` pour les liens
* etc...

Évitez les erreurs suivantes :

```
<span onclick="goToContact();">Contact</span>
```

**Et préférez ce code :**

```
<a href="/contact">Contact</a>
```
## Contenu alternatif

Définissez un contenu alternatif pour les objects multimédia tel que `<img>`, `<canvas>`, `<video>`, `<audio>`, `<object>`. Pour les images, remplissez l'attribut `alt=""`, pour les balises HTML5 audio/videos proposez des sous-titres. 

C'est un point important en terme d'accessibilité, par exemple le cas où un mal-voyant consulte le site, c'est le contenu alternatif qui sera lu à haute voix par un navigateur web spécialisé.

## Séparation contenu, structure et présentation

Séparez la structure définie par le balisage (markup HTML) de la présentation gérée par la feuilles de styles (CSS). N'utilisez pas de styles inline ou encore de balises dépréciées telles que `<center>`, `<font>`, etc…

## Caractères spéciaux

N'utilisez pas les codes HTML/ISO tels que `&eacute;` ou `&#233;` pour afficher le caractère `é`, cette écriture est obsolète au sein d'un document en `utf-8`.

## Attributs

Utilisez des doubles guillemets `""` plutôt que des simples guillement `''` pour autourer les valeurs des attributs.

Inutile de spécifier l'attribut « type » sur les balises `<script>` (à moins que vous n'utilisez pas JavaScript) et `<link>` (à moins que vous n'utilisez pas CSS).

**Recommandé :**

```
<link rel="stylesheet" href="screen.css">
```
## Exemple document HTML5

```
<!doctype html>
<html lang="fr">
<head>
  <meta charset="utf-8">
  <title>Document HTML5</title>
  <link rel="stylesheet" href="css/screen.css">
  <script src="js/modernizr.js"></script>
</head>
<body>
  <div id="document">
    <header id="header">
      <p>Nom du site</p>
    </header>
    <nav id="navigation">
      <ul>
        <li><a href="#">Item 1</a></li>
        <li><a href="#">Item 2</a></li>
        <li><a href="#">Item 3</a></li>
        <li><a href="#">Item 4</a></li>
        <li><a href="#">Item 5</a></li>
      </ul>
    </nav>
    <section id="section">
      <h1>Titre de la page</h1>
      <article class="news">
        <h2>Titre de l'article</h2>
        <p>Lorem ipsum dolor sit amet, consectetur. adipisicing</p>
      </article>
      <article class="news">
        <h2>Titre de l'article</h2>
        <p>Dolor neque nisi repellat hic iste inventore.</p>
      </article>
    </section>
    <footer id="footer"></footer>
  </div>
  <script src="js/application.js"></script>
</body>
</html>
```

* * *

# ![image](./images/html5-css.png) CSS

@ TODO

* * *

# ![image](./images/html5-js.png) JavaScript

@ TODO

<!-- Highlight JS -->
<link rel="stylesheet" href="http://softwaremaniacs.org/media/soft/highlight/styles/monokai.css">
<script src="http://yandex.st/highlightjs/7.3/highlight.min.js"></script>
<script>
  hljs.initHighlightingOnLoad();
</script>
