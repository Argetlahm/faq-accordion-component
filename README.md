# Frontend Mentor - FAQ accordion card solution

This is a solution to the [FAQ accordion card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-card-XlyjD0Oam). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See hover states for all interactive elements on the page
- Hide/Show the answer to a question when the question is clicked

### Screenshot

![](images/screenshot.png)

### Links

- Solution URL: [Solution URL](https://www.frontendmentor.io/solutions/responsive-faq-accordion-component-with-flex-pure-css-no-javascript-7sT1AClygS)
- Live Site URL: [Live Site](https://argetlahm.github.io/faq-accordion-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

- How to create conditional CSS selector with pure CSS and no Javascript
- Using clipping path to partially crop the image as intended

This code create some conditional css that is triggered only on certain condition.
```css
/* rotate arrow when the button is focused */
.faq-title-container:focus svg {
    rotate: 180deg;
}

/* toggle description to appear when focus */
.li:focus-within .faq-desc {
    display: block;
}
```

### Useful resources

- [Clipping-path documentation](https://developer.mozilla.org/en-US/docs/Web/CSS/clip-path#syntax) - Very useful resource to learn about clipping path syntax and usage.

## Author

- Github - [Argetlahm](https://github.com/Argetlahm)
- Frontend Mentor - [@Argetlahm](https://www.frontendmentor.io/profile/Argetlahm)


