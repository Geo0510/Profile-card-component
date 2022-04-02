# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- Build out the project to the designs provided

### Screenshot

![](./images/Frontend-Mentor-Profile-card-component.png)

### Links

- Solution URL: [https://github.com/Geo0510/Profile-card-component]
- Live Site URL: [https://geo0510.github.io/Profile-card-component/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I've been learning uses of position and flexbox.

```html
<div class="card_cabeza">
  <img
    src="images/bg-pattern-card.svg"
    class="card_cabeza--imagen"
    alt="carta con patrones circulos azules"
  />
  <img
    src="images/image-victor.jpg"
    class="card_cabeza_img--profile"
    alt="Foto de victor un gran hombre"
  />
</div>
```

```css
.card_cabeza_img--profile {
  position: absolute;
  top: 100px;
  left: 150px;
  background-color: #fff;
  border: 5px solid #fff;
  border-radius: 50%;
}
```

### Continued development

More flexbox and position with grid as well.

## Author

- Frontend Mentor - [@Geo0510](https://www.frontendmentor.io/profile/Geo0510)
- Github - [@Geo0510](https://github.com/Geo0510)
