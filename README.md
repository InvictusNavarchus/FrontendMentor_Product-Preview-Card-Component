# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
    -[Desktop](#desktop)
    -[Mobile](#mobile)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

#### Desktop

![Desktop Preview](./screenshots/desktop.png)

#### Mobile
![Mobile Preview](./screenshots/mobile.png)

### Links

- Solution URL: [Github Repo](https://github.com/invictus1032/FrontendMentor_Product-Preview-Card-Component)
- Live Site URL: [Netlify](https://fem-invictus1032-1.netlify.app/)

## My process

### Built with

- HTML5
- Tailwind CSS
  - Flex
  - Grid
- Mobile-first workflow

### What I learned

#### Live Server

I always had issues with live server whenever I work with tailwindcss. Sometimes only the HTML is updated, not the CSS. I suspect the live server extension I doesn't always notice if the CSS is updated. While working on this project, I found a live server that accurately keeps track of both the HTML and the CSS: [Five Server](https://marketplace.visualstudio.com/items?itemName=yandeu.five-server). It helps a lot. 

#### CSS Trick

There's always a CSS issue whenever I work with CSS. This time, the issue was making both the image card and the description card to be the same width. The solution I found on the internet is to give both cards these flex properties:

```css
.card {
  flex-grow: 1
  flex-shrink: 1
  flex-basis: 0
}
/* or simply */
.card {
  flex: 1 1 0
}
```

### Useful resources

- [Five Server](https://marketplace.visualstudio.com/items?itemName=yandeu.five-server) - This has now become my main live server tool
- [Stackoverflow: Even Width Flex Items](https://stackoverflow.com/questions/29503227/how-to-make-flexbox-items-the-same-size)

## Author

[@invictus1032](https://www.frontendmentor.io/profile/invictus1032)