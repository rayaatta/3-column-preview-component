# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)
### Links

- Solution URL: [https://github.com/rayaatta/3-column-preview-component](https://github.com/rayaatta/3-column-preview-component)
- Live Site URL: [https://rayaatta.github.io/3-column-preview-component/](https://rayaatta.github.io/3-column-preview-component/)
## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- CSS variables
- Mobile-first workflow
### What I learned

I learned tht styles fom one media query can flow into another as long as the argument is still true.
for example:```css 
@media screen and (min-width:500px) {
    body {
        justify-content:center;
    }

        @media screen and (min-width:800px) {
        /* i do not need to repeat the justify-content:center;
        for the body because the screen size is still above 500pixles and therefore the style is inherited here*/
    }
    ```
### Continued development

i want to learn how to use both flex-box and grid in the same layout to achieve better organisation

## Author

- Name - Raya-atta
- Frontend Mentor - [@rayatta](https://www.frontendmentor.io/profile/rayaatta)
