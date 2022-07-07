# Frontend Mentor - Space tourism website solution

[![Netlify Status](https://api.netlify.com/api/v1/badges/b08120ef-3182-4009-897d-27ec3b3a3d08/deploy-status)](https://app.netlify.com/sites/space-website-frontend-challenge/deploys)

 [Checkout the live site here](https://space-website-frontend-challenge.netlify.app)

This is a solution to the [Space tourism website challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/space-tourism-multipage-website-gRWj1URZ3). 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for each of the website's pages depending on their device's screen size
- See hover states for all interactive elements on the page
- View each page and be able to toggle between the tabs to see new information


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS utility classes
- Flexbox
- CSS Grid
- Vanilla JS
- Mobile-first workflow

### What I learned

- Responsive UX/UI development
- Using CSS grid and Flexbox to create responsive and dynamic layouts
  - grid is much more structured with a lot of control for the parent element 
- CSS camp - allows to set a min and max value for a certain property ( e.g font-size)
- The power of CSS custom properties and utility classes
- Dealing with browser support and accesibility
  - @supports CSS at-rule lets you specify declarations that depend on browser's support for one or more specific CSS feature - in this case I used the backdrop-filter property to create the glass effect for the navigation menu which is not supported by Firefox 
  - creating a sr-only(screen reader only) utility class for the the hamburger menu - onlu those using  a screen reader can access the word "Menu"
  - adding and aria-hidden class of ture to certain tags to hide the content from screen readers
  - adding a skip to content link is an internal navigation link that help users move around a page added for accesibility enhancement. This lets keyboard users and screen readers jump from the top of the page to the content without have to go through other elements on the page first.



### Continued development

- Refactor the code and build the website using REACT and CSS framworks Tailwind CSS

### Useful resources

- [Scrimba](https://www.srcimba.com) - This helped me to tacke those CSS challenges of using grid, custom properties and utility classes. 
- [FreeCodeCamp](https://www.freecodecamp.org) 






