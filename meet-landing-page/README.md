# Frontend Mentor - Meet landing page solution

This is a solution to the [Meet landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/meet-landing-page-rbTDS6OUR). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Desktop-first workflow

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
 <div class="page page-1"> 
    <div class="line"></div>
    <div class="circle">01</div>
  </div>
```
```css
.circle{
    color: #87879D;
    text-align: center;
    margin-top: 180px;
    border: 1px solid rgba(135, 135, 157, 0.25);
    border-radius: 50%;
 
    width: 56px;
    height: 56px;
    flex-shrink: 0;
    line-height: 56px;
}
.line{
    margin-bottom: 56px;
    width: 1px;
    height: 84px;
    background-color: #87879D;
    opacity: 0.25;
    z-index: 1;

    position: absolute;
    top: 53%;
    left: 50%;
    transform: translate(-35%, -35%); 
}
```

### Useful resources

- [Example resource 1](https://www.geeksforgeeks.org/how-to-target-desktop-tablet-and-mobile-using-media-query/) - This helped me for media query reason. I really liked this pattern and will use it going forward.

## Author

- Frontend Mentor - [@Faridah-11](https://www.frontendmentor.io/profile/faridah-11)
- Twitter - [fari_is_shy](https://www.twitter.com/fari_is_shy)

