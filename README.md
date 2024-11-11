# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./images/screenshot.png)

### Links

- Solution URL: (https://github.com/cfofana/product-preview-card-component-main)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

```html
<picture class="product-img">
        <source media="(min-width:700px)" srcset="images/image-product-desktop.jpg">
        <img src="images/image-product-mobile.jpg" alt="Gabrielle Essence Parfum lying on a table">
      </picture>
```
```css
@media (min-width:700px){
    .product {
      grid-template-columns: 1fr 1fr;
      --content-padding: 2rem;
    }
  }
  .btn:is(:hover, :focus) {
    background-color: var(--clr-primary-600);
  }
  .btn[data-icon="shopping-cart"]::before{
    content: "";
    width: 15px;
    height: 16px;
    background-image: url("images/icon-cart.svg");
  }
```



### Continued development

Css grid, media queries, picture tag, data attributes

### Useful resources

- [Data Attributes](https://www.w3schools.com/tags/att_data-.asp) - This helped me with data attributes. 
- [CSS Grid](https://www.w3schools.com/css/css_grid.asp) - This helped me get started with css grid.


## Author

- Website - [Ceesay Fofana](www.ceesayfofana.com)

## Acknowledgments

I acknowledge Kevin Powell for showing how to do the project.

