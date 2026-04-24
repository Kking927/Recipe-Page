# Frontend Mentor - Recipe Page solution

This is a solution to the [Recipe Page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./images/recipe-page-screenshot.png)

### Links

- [Solution URL](https://github.com/Kking927/Recipe-Page)
- [Live Site URL](https://kking927.github.io/Recipe-Page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- CSS Logical Properties

### What I learned
During this project, I focused on making my CSS more maintainable by using a central spacing scale in the :root. I also learned how to use CSS Logical Properties to ensure the layout remains consistent across different writing modes. I also chose to handle section spacing by adding a dedicated variable on the hr elements, keeping the layout's spacing logic centralized and easy to adjust.

```css
:root {
  --spacing-lg: 2rem; /* 32px */
  --hr-margin-block: var(--spacing-lg);
}

hr {
  border: 0;
  border-top: 1px solid var(--color-stone-150);
  margin-block: var(--hr-margin-block);
}
```

### Continued development
- **Fluid Typography:** Implementing the clamp() function to ensure font sizes scale smoothly and responsively between mobile and desktop resolutions.

- **CSS Container Queries:** Moving beyond Media Queries to use @container, allowing components like the recipe card to change their layout based on the width of their own container rather than the entire browser viewport.

### Useful resources

- **MDN Web Docs:** Logical Properties - This helped me understand why margin-block is often better than margin-top/bottom.

### Author

- Frontend Mentor - [@Kking927](https://www.frontendmentor.io/profile/Kking927)

