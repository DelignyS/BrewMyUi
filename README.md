# Projet THP

Ce projet utilise le kit UI Sketchy de Bootswatch pour styliser l'application.

## Fichier `creation.html.erb`

Le fichier `creation.html.erb` contient plusieurs éléments principaux :

1. **En-tête** : L'en-tête contient un titre `h1` et un paragraphe avec un lien vers le kit UI Sketchy.

2. **Cartes** : Il y a trois cartes. La première contient un formulaire, et les deux autres contiennent un court texte.

3. **Bannière** : La bannière contient plusieurs boutons de différentes couleurs.

4. **Barre de navigation** : La barre de navigation contient plusieurs liens et un formulaire de recherche.

## Intégration du kit UI Sketchy

Le kit UI Sketchy est intégré dans le projet en utilisant un lien CDN dans la balise `head` du fichier HTML. Cela permet d'utiliser les styles du kit UI sans avoir à utiliser l'asset pipeline de Rails.

Voici le lien CDN utilisé :

```html

<link href="https://stackpath.bootstrapcdn.com/bootswatch/4.5.2/sketchy/bootstrap.min.css" rel="stylesheet">

Pour utiliser les styles du kit UI, il suffit d'ajouter les classes CSS correspondantes aux éléments HTML.

```

