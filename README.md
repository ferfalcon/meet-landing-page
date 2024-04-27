# Frontend Mentor - Meet landing page solution

This is a solution to the [Meet landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/meet-landing-page-rbTDS6OUR).

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

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [https://github.com/ferfalcon/meet-landing-page](https://github.com/ferfalcon/meet-landing-page/)
- Live Site URL: [https://ferfalcon.github.io/meet-landing-page](https://ferfalcon.github.io/meet-landing-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Less](https://lesscss.org/) - CSS preprocessor for styles
- [BEM](https://getbem.com/) - Naming convention for HTML elements classification

### What I learned

Use multiple responsive images (Art direction) within the same element.

```html
<picture>
	<source media="(max-width: 48rem)" srcset="./images/image-footer.jpg">
	<source media="(max-width: 90rem)" srcset="./images/image-footer-tablet.jpg">
	<img class="stats-card__image" src="./images/image-footer-desktop.jpg" alt="Woman in videocall">
</picture>
```

### Useful resources

- [Responsive images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images/) - This helped me with the footer image.


## Author

- LinkedIn - [Fernando Falcon](https://www.linkedin.com/in/fernandofalcon/)
- Frontend Mentor - [@ferfalcon](https://www.frontendmentor.io/profile/ferfalcon/)
- Website - [ferfalcon.com](http://ferfalcon.com/)
- Twitter - [@fernandofalcon](https://www.twitter.com/fernandofalcon/)