# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

This project helped me practice **positioning elements with Flexbox**, using **CSS Grid for layout**, and handling **hover effects without affecting nested elements like SVGs**.

One of the things I’m proud of is handling the hover overlay effect on the image:

```css
.card-image::before {
  content: "";
  position: absolute;
  inset: 0;
  background-color: rgba(0, 255, 247, 0.5);
  opacity: 0;
  transition: opacity 0.3s ease;
}

.card-image:hover::before {
  opacity: 1;
}
```

### Continued development

In future projects, I want to keep improving my CSS animations and transitions for smoother hover states, as well as deepening my understanding of responsive design using both Flexbox and Grid.

## Author

- Frontend Mentor - @juanfeoru
- GitHub - @juanfeoru
