# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Screenshot](./images/screenshot.png)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned how to center a block depending on the viewport's height.

```css
.container {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 700px;
    height: calc(100vh - 60px);
}
```

## Author

- Frontend Mentor - [@LegendaryGhost](https://www.frontendmentor.io/profile/LegendaryGhost)

## Acknowledgments

Thanks to Princy (Github - [@plinsy](https://github.com/plinsy)) who helped me figuring out how to complete this challenge
