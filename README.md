# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- Build out the project to the designs provided

### Screenshot

![](https://ik.imagekit.io/c5xc1x6srka/screenshot/screen-profile-card_RDE6GZfnP.png?ik-sdk-version=javascript-1.4.3&updatedAt=1647199716206)

### Links

- Solution URL: [https://github.com/samsonsham/profile-card](https://github.com/samsonsham/profile-card)
- Live Site URL: [https://samsonsham.github.io/profile-card/](https://samsonsham.github.io/profile-card/)

## My process

- Set up SCSS file structure. Define all the styles given by style guide, including colours and font into SCSS files.
- Define components and setup corresponding DOM elements in HTML file.
- Mobile first, build each elements by with colours, alignment, and adjusting size.

### Built with

- Semantic HTML5 markup
- SCSS
- Flexbox
- Mobile-first workflow

### What I learned

- For `max-width` to work correctly, the element width should also be defined, e.g. `width: 100%`.
- Using `box-shadow` with proper config of offset and blur.

```css
.card {
  background-color: $clr-bg-card;
  display: flex;
  flex-direction: column;
  align-items: center;
  border-radius: 1rem;
  width: 100%;
  max-width: 24rem;
  box-shadow: 0 1rem 1rem $clr-shadow;
}
```

### Useful resources

- [Why would max-width not work on this?](https://stackoverflow.com/questions/14938428/why-would-max-width-not-work-on-this) - This helped me for using `max-width` correctly.

## Author

- Website - [Samson Sham](https://samson-sham-portfolio.vercel.app)
- Frontend Mentor - [@samsonsham](https://www.frontendmentor.io/profile/samsonsham)
- Twitter - [@samson_sham](https://www.twitter.com/samson_sham)
