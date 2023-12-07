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
    - [Useful resources](#useful-resources)
  - [Author](#author)
  - [Acknowledgments](#acknowledgments)
  - [Time estimate](#time-estimate)

**Note: Delete this note and update the table of contents based on what sections you keep.**

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

### Continued development

- list styling
- blend modes on images

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

[Kevin Powell](https://www.youtube.com/watch?v=TAA89nkEuhw)

 ## Time estimate 

 Expectation: 2 hrs
 Reality: 
- Start at 11:26 AM

 
