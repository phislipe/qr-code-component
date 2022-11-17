# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Screenshot

![Frontend Mentor - QR code component solution by Philipe Rocha](./images/screenshot.png)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/qr-code-component-html-css-a-WSl-ddwv](https://www.frontendmentor.io/solutions/qr-code-component-html-css-a-WSl-ddwv)
- Live Site URL: [https://phislipe.github.io/qr-code-component](https://phislipe.github.io/qr-code-component)

## My process

### Built with

- HTML
- CSS

### What I learned

Doing this project was way more interesting than I thought it would be. I struggled a bit with how to center a div vertically. After some research, I discovered I was only missing the height property for the flex to work correctly.

```css
body {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100vh;
}
```

After much refactoring, I was able to make the QR code card stay centered on the page using less code.

Also pretend to look more into `box-shadow`, since I'm not really happy with what it is right now.

### Useful resources

- [Stack Overflow](https://stackoverflow.com/questions/396145/how-can-i-vertically-center-a-div-element-for-all-browsers-using-css) - This 13-year-old post helped me figure out how to center a div vertically. At first, I was using three divs to be able to center one of them vertically. After reading through it, I made it work properly with `flexbox`(a much simpler solution).

## Author

- 🌐 Website - [phislipe.dev](https://phislipe.dev)
- 🪪 LinkedIn - [Philipe Rocha](https://www.linkedin.com/in/phislipe/)
- 🎨 Frontend Mentor - [@phislipe](https://www.frontendmentor.io/profile/yourusername)
