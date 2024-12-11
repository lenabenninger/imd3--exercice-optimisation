# Exercice optimisation

Rendez vous sur la page `index.html`. Celle-ci a été conçu par quelqu'un qui ne connait rien aux normes de développement web et d'accessibilité. A vous de faire en sorte d'améliorer ce site !

## Installation

```
npm install
npm run dev
```

## Etape 1

Ouvrez l'inspecteur et allez dans l'onglet "Lighthouse". Faites un test et voyez les points d'amélioration cités.

## Etape 2

Commencez par optimiser tout ce qui est relatif à l'import des assets:

- les images (👉 pensez à exploiter Parcel)
- le code CSS
- les libriares JavaScript et CSS (vérifiez également lesquelles sont utilisées ou non)
- le code JavaScript

## Etape 3

Modifier la structure HTML pour qu'elle fasse plus de sens sémantiquement et soit accessible

- Pensez aux textes alternatifs pour les images
- Réfléchissez à la hiérarchie du contenu, notamment des titres
- Pensez à utiliser des balises sémantiques lorsque c'est possible (par ex. header, footer, main, label, etc.)
- Utilisez l'attribut "Loading" pour les images lorsque c'est pertinent ([documentation](https://developer.mozilla.org/fr/docs/Web/Performance/Lazy_loading))

## Etape 4

Améliorez le CSS pour un rendu plus accessible

- Pensez au contrate des couleurs
- Pensez à la taille du texte, afin qu'elle soit relative aux préférences de l'utilisateur.trice (👉 unité de typographie comme `rem`)
- Pensez au responsive (👉 Bootstrap Grid)

## Etape 5

Une fois vos modifications faites, relancez Lighthouse et vérifiez si votre score s'est amélioré.
