# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](./images/screenshot.png)

### Links

- Solution URL: [Solution](https://github.com/AlexdelCarmen/single-price-grid-component)
- Live Site URL: [Live site](https://alexdelcarmen.github.io/single-price-grid-component/)

## My process

As usual, I created the HTML structure first, next I added some custom CSS styles, then proceeded to style the mobile layout for the website.  I ended with making a simple media query to support desktop layouts.  
### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

Improved my box shadow technique, I also started including vendor prefixes:

```css

.sign-up {
  background-color: var(--main-color2);
  margin: 0 auto;
  width: 100%;
  color: var(--neutral-color1);
  font-size: var(--para-size);
  font-weight: 700;
  padding: 1rem 0;
  border-radius: 5px;
  margin-bottom: 1rem;
  box-shadow: -1px 10px 15px -1px rgba(0, 0, 0, 0.52);
  -webkit-box-shadow: -1px 10px 15px -1px rgba(0, 0, 0, 0.52);
  -moz-box-shadow: -1px 10px 15px -1px rgba(0, 0, 0, 0.52);
  cursor: pointer;
}



```

### Continued development

Still got to practice more my responsive layouts.  

- [W3Schools article on multiple backgrounds on an HTML element](https://www.w3schools.com/css/) - General CSS reference.


## Author

- Website - [Github Profile](https://github.com/AlexdelCarmen)
- Frontend Mentor - [@AlexdelCarmen](https://www.frontendmentor.io/profile/AlexdelCarmen)
- Twitter - [@AlekBorchov](https://twitter.com/AlekBorchov)

## Acknowledgments

To mom, I'll get you out one day.  