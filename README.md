# Frontend Mentor - Huddle landing page with curved sections solution

This is a solution to the [Huddle landing page with curved sections challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-curved-sections-5ca5ecd01e82137ec91a50f2). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![Solution PC](./images/Solution%20PC.png)
![Solution Mobile](./images/Solution%Mobile.png)

### Links

- Solution URL: [Solution](https://github.com/fidellim/Huddle-Landing-Page-with-Curved-Sections)
- Live Site URL: [Live Site](https://nifty-thompson-42c429.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I have learned on how to change an image's color using CSS filter. I was able to be familiarized with what "+" selector does as well.

```css
.footer-logo {
	filter: brightness(0) invert(1);
}

input[type="text"]:active + .input-err {
	display: block;
}

.cs-top-1 {
	content: url(./images/bg-section-top-mobile-1.svg);
}
```

### Continued development

I would like to continue understanding what CSS filter does. It does a lot more so looking forward to learn more from it.

### Useful resources

- [Selector "+"](https://www.w3schools.com/cssref/css_selectors.asp) - I was able to understand on how to use the "+" selector.
- [Remove outline](https://stackoverflow.com/questions/2943548/how-to-reset-remove-chromes-input-highlighting-focus-border) - This helped me remove the outline on input tag when it is in active state.
- [CSS Filter](https://stackoverflow.com/questions/24224112/css-filter-make-color-image-with-transparency-white) - I was able to change the color of the image (svg) using filter.
- [CSS :active selector](https://www.w3schools.com/cssref/sel_active.asp)- I was have an understanding on what :active selector does.
- [Change Color of SVG](https://css-tricks.com/change-color-of-svg-on-hover/) - This was able to help me change the color of svg file but eventually I thought of using `<img>` tag instead so I can easily scale its size.
- [Replace image using CSS](https://stackoverflow.com/questions/2182716/is-it-possible-to-set-the-equivalent-of-a-src-attribute-of-an-img-tag-in-css) - I was to replace the current images I have with another one with this solution.

## Author

- Website - [Fidel Lim](https://fidellim-portfolio.netlify.app/)
- Frontend Mentor - [@fidellim](https://www.frontendmentor.io/profile/fidellim)
- Github - [@fidellim](https://github.com/fidellim)
