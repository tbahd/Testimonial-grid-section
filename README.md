# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./designs/Desktop%20Design.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

I learnt how to work with grid layout in a real situation outside tutorial. Also learnt how to position backgrounds properly ie the quotaion mark.

```css
.purple{
    background-color: var(--Moderateviolet);
    background-image: url(/images/bg-pattern-quotation.svg);
    background-repeat: no-repeat;
    background-position: 80% 0;
}
.container{
    width: 1200px;
    height: auto;
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 1rem;
    margin: auto;
    }
```

### Continued development

I'll continue leraning more on grid layout.

## Author

- Website - [Tbahd](https://olukolejames.netlify.app)
- Frontend Mentor - [@tbahd](https://www.frontendmentor.io/profile/tbahd)
- Twitter - [@tbahd](https://www.twitter.com/tbahd2)
