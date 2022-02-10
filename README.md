# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - Stats preview card component solution](#frontend-mentor---stats-preview-card-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
  - [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./images/screenshot.png)

### Links

- [Code Source](https://github.com/zougari47/stats-preview-card-component-main)
- [Live Demo](https://zougari47.github.io/stats-preview-card-component-main/)

## My process

### Built with

- HTML
- CSS custom properties
- Flexbox
- Mobile-first workflowstyles

### What I learned

Practice more media queries css.

How I made overlay effect:

```css
.image {
  width: 100%;
  height: 35%;
  background: url(./images/image-header-mobile.jpg) no-repeat center/cover;
  position: relative;
}

.image:before {
  content: '';
  width: 100%;
  height: 100%;
  position: absolute;
  background: var(--Soft-violet);
  opacity: 0.65;
  top: 0;
  left: 0;
}
```

## Author

- CodePen - [@zougari47](https://codepen.io/zougari47)
- Frontend Mentor - [@zougari47](https://www.frontendmentor.io/profile/zougari47)
- Twitter - [@zougari47](https://www.twitter.com/zougari47)
