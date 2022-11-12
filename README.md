# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)

- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)

- [Author](#author)


## Overview

This is my solution to the product preview card challenge with mobile responsiveness.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements


## My process

started off with creating HTML and CSS properties. Eventually focused on each section to ensure responsiveness.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid


### What I learned

Using media queries to make a mobile version of the page was very challening. I was very happy to discover and make the responsiveness to mobile and desktop versions work. A highlight of the code below that I am proud of:

@media all and (max-width: 900px) {
    .perfume-image {
        display: none;
    }

    .productimage {
        display: block;
        align-items: center;
        justify-content: center;
    }

    .perfume-mobile {
        display: flex;
        width: 60%;
        background-position: center;
        background-size: cover;
        border-top-left-radius: 10px;
        border-top-right-radius: 10px;
        object-fit: cover;
    }

    .advert {
        background-color: var(--white);
        width: 60%;
        display: flex;
        flex-direction: column;
        row-gap: 15x;
        padding: 20px 40px;
        gap: 10px;
        border-top-right-radius: 0px;
        border-bottom-left-radius: 10px;
    }
}


### Continued development
Continue to work on CSS properties such as flexbox and content alignment to make a more appealing website for users. Also focus on pracitcing more in using media queries to have a responsive website for desktop and mobile devices.



## Author

Martin L.
