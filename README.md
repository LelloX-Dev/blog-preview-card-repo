# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

---

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![Screenshot of the blog preview card](./design/Screenshot.png)

### Links

- Solution URL: [Solution Code](https://github.com/LelloX-Dev/blog-preview-card-repo)
- Live Site URL: [Live site](https://lellox-dev.github.io/blog-preview-card-repo/)

---

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Custom local font with `@font-face`

### What I learned

This project helped me improve layout and typographic styling using custom fonts, local asset handling, and hover states. It also reinforced best practices for semantic HTML structure.

#### Example: Custom font integration using `@font-face`

```css
@font-face {
  font-family: "Figtree";
  src: url("./assets/fonts/Figtree-VariableFont_wght.ttf") format("truetype");
  font-weight: 100 900;
  font-style: normal;
}
```

#### Example: Card with shadow and hover effect

```css
.blog-card {
  box-shadow: 8px 8px 0 var(--Gray-950--);
  transition: box-shadow 0.3s ease;
}
.title:hover {
  color: var(--Yellow--);
  cursor: pointer;
}
```

---

## Author

- Frontend Mentor - [@LelloX-Dev](https://www.frontendmentor.io/profile/LelloX-Dev)
