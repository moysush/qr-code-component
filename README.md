# QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H).

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### Screenshot

![](./images/screenshot.png)

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
