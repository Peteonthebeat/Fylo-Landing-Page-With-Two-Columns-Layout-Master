# Frontend Mentor - Fylo landing page with two column layout solution

This is a solution to the [Fylo landing page with two column layout challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-landing-page-with-two-column-layout-5ca5ef041e82137ec91a50f5).

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [https://peteonthebeat.github.io/Fylo-Landing-Page-With-Two-Columns-Layout-Master/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I got to practice Flexbox and Grid, and also adding images between sections like the curve. I also got more accustomed to using SASS. Thanks to these chalenges, I'm feeling very confident in making proper header menus and using <ul> for various purpose.

```html
<header>
  <img class="logo" src="/images/logo.svg" alt="logo" />
  <ul>
    <li><a href="#" target="_blank">Features</a></li>
    <li><a href="#" target="_blank">Team</a></li>
    <li><a href="#" target="_blank">Sign In</a></li>
  </ul>
</header>
```

```css
header {
  padding: 2em 1.5em;
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: space-between;
  font-family: "Raleway", sans-serif;
  img {
    width: 5em;
  }
  ul {
    display: flex;
    justify-content: space-between;
    li {
      margin: 0 0.8em;
      font-size: 0.8em;
      font-weight: 400;
      a {
        color: black;
      }
    }
  }

```

### Continued development

I'd like to learn how to do those alert messages on the inputs; also how to make a proper hover effect on my SVGs. Besides that I plan to continue with the flexbox and grid, such as with positioning and using z-index properly. I also ordered 2 books on JS, and can't wait for them to come.

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@peteonthebeat](https://www.frontendmentor.io/profile/peteonthebeat)

