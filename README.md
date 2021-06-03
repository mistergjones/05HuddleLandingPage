# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

-   [Overview](#overview)
    -   [The challenge](#the-challenge)
    -   [Screenshot](#screenshot)
    -   [Links](#links)
-   [Built with](#built-with)
-   [What I learned](#what-i-learned)

-   [Author](#author)

## Overview

### The challenge

Users should be able to:

-   View the optimal layout for the page depending on their device's screen size
-   See hover states for all interactive elements on the page

### Screenshot

![](./screenshot.png)

### Links

-   Solution URL: [Add solution URL here](https://github.com/mistergjones/05HuddleLandingPage)
-   Live Site URL: [Add live site URL here](https://mistergjones.github.io/05HuddleLandingPage/)

### Built with

-   Semantic HTML5 markup
-   CSS custom properties
-   Flexbox
-   CSS Grid
-   Mobile-first workflow

### What I learned

Using DISPLAY FLEX and direction of COLUMN makes mobile friendly rendering nice.

```css
@media screen and (max-width: 375px) {
    .flex-container {
        display: flex;
        flex-direction: column;
        padding-left: 2rem;
        padding-right: 2rem;
    }
```

Using the :hover pseudo class changes colour when a user hovers over the button.

## Author

-   Website - [Glen Jones](https://www.glenjones.com.au)
