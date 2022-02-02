# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62).

## Table of contents

-   [Overview](#overview)
    -   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
    -   [Useful resources](#useful-resources)
-   [Author](#author)

## Overview
![](./images/solution.png)


### Links

-   Solution URL: [Github code source ](https://your-solution-url.com)
-   Live Site URL: [website](https://your-live-site-url.com)

## My process

### Built with

-   Semantic HTML5 markup
-   CSS custom properties
-   Flexbox
-   CSS Grid


### What I learned

Je appris comment créer un effet superposer (overlay)

Mais, je ne suis pas aller dans la même logique où on utilise javascript pour activer et désactiver l'effet (overlay)

EXEMPLE :

Je donc créer un élément html un div container pour ajouter mon image avec le css

```html
<div class="card__img-overlay"></div>
```

Et puis, avec la propriétés css mode de fusion d'arrière-plan
(background-blend-mode) cette propriété définit comment un élément
background-image doit se mélanger avec son background-color:

EXEMPLE :

```css
.card__img-overlay {
    background-image: url("./images/image-header-desktop.jpg");
    background-color: hsl(277, 64%, 61%);
    background-blend-mode: multiply;
}
```

C'est le lien:

-  [CSS tricks](https://css-tricks.com/almanac/properties/b/background-blend-mode/)


### Useful resources

-   [MDN Web Docs mozilla](https://developer.mozilla.org/fr/) - This helped me for XYZ reason.

-   [W3schools ](https://www.w3schools.com/) - This is an amazing article which helped me finally understand XYZ.

## Author

-   Frontend Mentor - [@steven](https://www.frontendmentor.io/profile/yourusername)
-   Twitter - [@steven](https://www.twitter.com/yourusername)
