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
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./screenshot.jpg)


### Links

- Solution URL: https://www.frontendmentor.io/solutions/testimonial-grid-section-with-css-grid-Eqco7b8ze-
- Live Site URL:(https://bigboyemma20.github.io/testimonials-grid-section/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Responsive design principles

### What I learned

This project was a great opportunity to practice CSS Grid layout techniques. I used a combination of grid and flexbox to create a responsive testimonial section that adapts to different screen sizes.
One of the key aspects I implemented was using CSS Grid for the overall layout and Flexbox for aligning items within each card:

```html
<main class="container">
  <div class="card card-1 white-text">
    <!-- Card content -->
  </div>
  <!-- More cards -->
</main>
```
```css
.container{
        display: grid;
        grid-gap: 1.5em;
        max-width: 75em;
        margin: 0 auto
    }
    
    .card{
        display:flex;
        flex-wrap: wrap;
        align-items: center;
        border-radius: .7em;
        padding-block: 2em;
        padding-inline: 2em;
        transition:transform 0.3s ease;
    }
```

### Continued development

In future projects, I want to focus on:

- Improving my CSS organization by using a more structured approach like BEM
- Adding more interactive elements and animations
- Optimizing accessibility features
- Implementing better responsive image handling
- Creating more refined hover states

### Useful resources

- MDN Web Docs on CSS Grid - This helped me understand grid layout concepts and how to implement them effectively.
- CSS-Tricks Guide to Flexbox - An excellent resource that helped me understand Flexbox layout.


## Author

- - My Github - [Emmanuel Quarm](https://github.com/bigboyemma20)
- Frontend Mentor - [@bigboyemma20](https://www.frontendmentor.io/profile/bigboyemma20)
- Twitter - [@freshmanuel11](https://www.twitter.com/freshmanuel11)
