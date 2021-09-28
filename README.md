# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](assets/screenshots/mobile.png)
![](assets/screenshots/desktop.png)


### Links

- Solution URL: [Github](https://github.com/erelita/3-column-preview-card.git)
- Live Site URL: [Github](https://erelita.github.io/3-column-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

This was easier compare to the first few ones I did. I can't believe I just needed two lines of Grid CSS to make it responsive for 1024px and above width.


```css
.column-container {
  width: 920px;
  height: 500px;
  display: grid;
  grid-template-columns: repeat(3, 1fr);
}
```


### Continued development

I want to do more challenges with Grid CSS in the future. I want to be really good at it so I can make layouts more responsive.

## Author

- Github - [Erelita](https://github.com/erelita)
- Frontend Mentor - [@erelita](https://www.frontendmentor.io/profile/erelita)
