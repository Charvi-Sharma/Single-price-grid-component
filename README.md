# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](./images/Screenshot_Desktop.png)
![](./images/Screenshot_Mobile.png)

### Links

- Solution URL: https://www.frontendmentor.io/solutions/responsive-pricing-component-using-css-grid-PRob7ANEC0
- Live Site URL:  https://charvi-sharma.github.io/Single-price-grid-component/

## My process

### Built with

- HTML
- CSS custom properties
- CSS Grid
- CSS Media Queries

### What I learned

- Using CSS Grid

```css
.container{
    display: grid;
    margin: 2em 20em;
    grid-template-rows: repeat(2,1fr);
    grid-template-columns: repeat(2,1fr);
    row-gap: 0px;
    column-gap: 0px;
  }
```
- Using Media Queries for reponsiveness

```css
@media only screen and (max-width:376px){
    .container{
      margin: 2em 2em;
      grid-template-columns: 1fr;
      grid-template-rows: 1fr 1fr 1fr;
    }
    .item1{
    background-color: white;
    grid-column-start: 1;
    grid-column-end: 2;
  }
  .btn{
    padding: 1em 5em;
    margin: 2em 1em;
  }
  }
```

## Author

- Git Hub	-	https://github.com/Charvi-Sharma
- Leet Code	-	https://leetcode.com/Charvi-Sharma
