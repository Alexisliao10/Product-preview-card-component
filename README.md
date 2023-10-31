# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

te and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- BEM Methodology
- SASS
- Flexbox
- Mobile-first workflow

### What I learned

I learned to use BEM Methology for better code reading and to avoid using high specifity selectors like the element tag and id.

```html
 <main class="main">
    <div class="card">
      <div class="card__aside">
        <img class="card__image" src="../src/images/image-product-mobile.jpg" alt="Gabrielle Chanel">
      </div>```
```
```scss
.card {
  display: flex;
  flex-direction: column;
  justify-content: center;
  margin-top: 20px;
  max-width: 340px;
  background-color: $secondary-white;
  border-radius: 10px;

  &__image {
    border-radius: 10px 10px 0 0;
    width: 100%;
  }
```

### Continued development

I would like to learn tailwind CSS for future projects and react.

### Useful resources

- [https://bem-cheat-sheet.9elements.com] - This website helped me to named my classes in a fast and easy way.
- [https://9elements.com/css-rule-order/] - This is useful for organize you CSS properties.
- [https://css-tricks.com/snippets/css/a-guide-to-flexbox/] - Simple and complete guide for flexbox.

## Author

- Frontend Mentor - [@Alexisliao10] https://www.frontendmentor.io/profile/Alexisliao10)
