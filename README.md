# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://kwokkw.github.io/stats-preview-card-component-main/). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Stats preview card component solution](#frontend-mentor---stats-preview-card-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
  - [Author](#author)
  - [Acknowledgments](#acknowledgments)
  - [Time estimate](#time-estimate)

## Overview

A stats preview card component

Components are built using basic HTML and css. 

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Links

- Solution URL: [github repo](https://github.com/kwokkw/stats-preview-card-component-main)
- Live Site URL: [live site](https://kwokkw.github.io/stats-preview-card-component-main/)

## My process

- HTML
- CSS

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I am more comfortable with the following css reset:

```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
```

MIX BLEND MODE

```html
<div class="mix-blend-mode">
  <picture>
    <source media="(min-width: 48rem)" srcset="images/image-header-desktop.jpg">
    <img src="images/image-header-mobile.jpg" alt="Header image" width="654" height="480">
  </picture>
</div>
```

```css
.mix-blend-mode {
    background-color: var(--accent);
}

img {
    mix-blend-mode: multiply;
}
```

Padding vs Margin 
- Padding doesn't collapse 
- Margin collapses by default
- Use Padding: 
  - When you want to control the space inside an element, such as adjusting the spacing between a box and the text or other content inside it.
- Use Margin: 
  - When you want to create space between elements, ensuring proper spacing and layout separation.

The Order of the Items

```css
.card-container {
        display: grid;
        grid-template-columns: 1fr 1fr;
}

.mix-blend-mode {
        grid-area: 1/ 2/ 2/ 3;
}

.text-container {
        /* grid-row-start, grid-column-start, grid-row-end and the grid-column-end properties. */
        grid-area: 1/ 1/ 2/ 2;
}
```


### Continued development

- list styling
- blend modes on images

## Author

- Frontend Mentor - [@kwokkw](https://www.frontendmentor.io/profile/kwokkw)

## Acknowledgments

[Kevin Powell](https://www.youtube.com/watch?v=TAA89nkEuhw)

Grace Snow [Understanding When to Use Padding vs. Margin in CSS - FED Mentor](https://fedmentor.dev/posts/padding-margin/)

 ## Time estimate 

 Expectation: 2 hrs
 Reality: 5 hrs

 
