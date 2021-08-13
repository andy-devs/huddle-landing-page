# Frontend Mentor - Huddle landing page with single introductory section solution

This is my solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0).

## Table of contents

-   [Overview](#overview)
    -   [The challenge](#the-challenge)
    -   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
    -   [Continued development](#continued-development)
    -   [Useful resources](#useful-resources)

## Overview

### The challenge

Users should be able to:

-   View the optimal layout for the page depending on their device's screen size
-   See hover states for all interactive elements on the page

### Links

-   Solution URL: [Add solution URL here](https://github.com/andy-devs/huddle-landing-page)
-   Live Site URL: [Add live site URL here](https://andy-devs.github.io/huddle-landing-page/)

## My process

### Built with

-   Semantic HTML5 markup
-   CSS
-   Flexbox
-   CSS Grid
-   Desktop-first workflow
-   [Box-shadow generator](https://active-vision.ru/icon/box-shadow/)
-   [Font Awesome](https://fontawesome.com/) - Icons

### What I learned

I leaned how to implement CSS Grid on basic level, tried applying box shadow to a button and continued to work on adaptive layout. Although It took me some time, It was fun to do this one :)

Code Snippets:

```css
main {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr;
    grid-template-rows: 15% 75% 10%;
    grid-template-areas:
        "header . . ."
        "preview preview info info"
        ". . . footer";
}
```

### Continued development

I think I'll try something a little bit harder next time to test my skills.

### Useful resources

Couple of useful resources are in My Process - Build with
