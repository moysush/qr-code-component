# QR Code Component

This is a solution to the [Frontend Mentor](https://www.frontendmentor.io/solutions/css-css-flexbox-html-tBHfY8Pkwn).

Live Site: [QR Code Component](https://sushcod3.github.io/qr-code-component/)

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### Screenshot

![screenshot](./images/screenshot.png)

### Built with

- Tailwind CSS

### What I learned

- Using 100vh will select the 100% of the viewport and it enabled me to center the element on the page along with flexbox. Setting height to min-height will not cut off the height on smaller screen.

```css
body {
  display: flex;
  align-items: center;
  justify-content: center;
  min-height: 100vh;
}

```
