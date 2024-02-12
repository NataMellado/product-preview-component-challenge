# Frontend Mentor - Product preview card component solution

![](./design/desktop-preview.jpg)

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [https://natamellado.github.io/product-preview-component-challenge/](https://natamellado.github.io/product-preview-component-challenge/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

* The _source_ element provide different image sources based on the screen width. 
```html
<picture class="card-image">
    <source media="(max-width: 768px)" srcset="./images/image-product-mobile.jpg">
    <source media="(min-width: 769px)" srcset="./images/image-product-desktop.jpg">
    <img src="imagen-desktop.jpg" alt="Gabrielle Eau de Parfume">
</picture>
```
* Break-word allows the browser to break words to prevent overflow
```css
overflow-wrap: break-word;
```

* In Adobe XD, the formula for converting letter spacing values to em is in fractions of 1/1000 of the font size
```css
letter-spacing: 0.33em ;
letter-spacing: -0.012em;
````