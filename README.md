# Frontend Mentor - NFT Preview Card Component Solution

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

![](https://i.ibb.co/LxHfX0k/Screenshot-2023-04-06-151204.png)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/nft-preview-card-component-using-html-and-css-36VPezGCjY](https://www.frontendmentor.io/solutions/nft-preview-card-component-using-html-and-css-36VPezGCjY)
- Live Site URL: [https://https://incandescent-selkie-0e3c3a.netlify.app/](https://incandescent-selkie-0e3c3a.netlify.app/)

## My process

### Built with

- HTML
- CSS
- Flexbox

### What I learnt

I have learnt how to place image on image and create a overlay effect while we hover that property.

```css
.overlay {
  display: flex;
  position: absolute;
  top: 25px;
  left: 25px;
  width: 350px;
  height: 350px;
  opacity: 0;
  transition: 0.5s ease;
  background-color: hsl(178, 100%, 50%);
  justify-content: center;
  align-items: center;
  border-radius: 15px;
}

.container:hover .overlay {
  opacity: 0.5;
  cursor: pointer;
}
```

### Continued development

For future projects I need to focus on using more advanced CSS to create effects.

### Useful resources

- [How To Create an Overlay Image Icon](https://www.w3schools.com/howto/howto_css_image_overlay_icon.asp) - This helped me to add an overlay to the image on hover.

## Author

- Website - [Asif Akhtar](https://asifakhtar.com/)
- Frontend Mentor - [@imasifakhtar](https://www.frontendmentor.io/profile/imasifakhtar)
- Twitter - [@imasifakhtar](https://twitter.com/imasifakhtar)
- LinkedIn - [@imasifakhtar](https://www.linkedin.com/in/imasifakhtar/)
