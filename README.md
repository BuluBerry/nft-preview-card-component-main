# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./assets/design/Frontend%20Mentor%20NFT%20preview%20card%20component.png)
![](./assets/design/Frontend%20Mentor%20NFT%20preview%20card%20component-mobile.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5
- CSS
- Flexbox

### What I learned

This wasn't the first time using :hover, but it was the first time adding anoter image on top of each other. 



```css
.image__overlay{
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: hsla(178, 100%, 50%, 50.3%);
    border-radius: 8px;
    display: flex;
    justify-content: center;
    align-items: center;
    opacity: 0;
}

.image__overlay:hover{
    opacity: 1;
}
```


### Continued development

I will definitely be wokring on overlaying stuff in the future, I really love the affect. I also need to work on 100% understanding the poition property. 
### Useful resources

- (https://www.youtube.com/watch?v=exb2ab72Xhs&t=621s) - I watched a youtube tutorial to help me figure out how to do the hover overlay! It explained the process really well. 


## Author

- Frontend Mentor - [@BuluBerry](https://www.frontendmentor.io/profile/BuluBerry)
