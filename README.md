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

## Overview

Product preview card component

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

Desktop version
![](./screenshot.jpeg)

### Links

- Solution URL: (https://www.frontendmentor.io/solutions/product-preview-card-component-mpvQd00V0f)
- Live Site URL: (https://product-preview-card-component-eosin-ten.vercel.app/)

## My process
First I checked the mobile and desktop design, I decided to start with a first mobile approach, then I defined the html structure and proceeded with the css styles, later I added media queries for diferent screen devices, finally I checked everything was fine. 

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<!-- My html 5 markup -->
<div class="card">
    <main>
      <div class="image"></div>
      <div class="right">

        <section>
        
          <figcaption class="fig">Perfume</figcaption>
          <h1>Gabrielle Essence Eau De Parfum</h1>
          <p class="text">A floral, solar and voluptuous interpretation composed by Olivier Polge, 
            Perfumer-Creator for the House of CHANEL.</p>
          
          <div class="price"> 
            <p class="huge">$149.99</p>
            <p class="non-huge">$169.99</p>
          </div>
  
          <button>
            <p>
              <img class="icon" src="./images/icon-cart.svg" alt="icon-cart">
              Add to Cart
            </p>
          </button>
  
        </section>

      </div>
    </main>
  </div>
```
```css
/* I used this media queries */
/* Mobile */
@media (min-width: 375px) and (max-width: 768px) { ... }
/* Ipad */
@media (min-width: 768px) and (max-width: 1440px) { ... }
/* Desktop */
@media (min-width: 1441px) { .. }
```

### Continued development

In future projects I would like to implement:
1. Sass/Less
2. BEM

### Useful resources

- [Media queries](https://torquemag.io/2021/08/media-queries-guide/) - This website helped me to get the exact media queries.
- [Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox) - This website was very useful to remember specific features of flexbox used in this project.

## Author

- Website - [Armando Gutiérrez](https://arpwn.vercel.app/)
- Frontend Mentor - [@armandonery](https://www.frontendmentor.io/profile/armandonery)
- Twitter - [@armandogtz_8](https://www.twitter.com/armandogtz_8)