# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). This was my first challenge, built while learning HTML and CSS from scratch.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### Screenshot

![QR code component screenshot](./screenshot.jpeg)

### Links

- Solution URL: [Frontend Mentor solution](https://www.frontendmentor.io/solutions/qr-code-component-using-semantic-html-and-css-flexbox-HRyzjhc307)
- Live Site URL: [qr-code-component-one-zeta.vercel.app](https://qr-code-component-one-zeta.vercel.app)

## My process

### Built with

- Semantic HTML5 markup
- External CSS stylesheet
- Flexbox
- Google Fonts (Outfit)

### What I learned

**The box model and `box-sizing`**

My card was wider than expected because, by default, padding is added on top of the width. Using `border-box` makes the width include padding and border:

```css
* {
  box-sizing: border-box;
}
```

**Centering with Flexbox**

To center the card on the screen, I turned the `body` into a flex container and gave it the full viewport height:

```css
body {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  margin: 0;
}
```

**Selectors vs. properties**

A selector defines *who* gets styled (`.attribution`, `h1`), and a property defines *what* changes (`margin-top`, `color`). Properties always go inside the selector's braces.

### Continued development

- Use `rem` instead of `px` for better accessibility
- Learn `position` to center only the card, keeping the footer out of the flex flow
- Make smaller, more frequent commits to show my process

### AI Collaboration

I used Claude as a tutor, learning one concept at a time (HTML structure, linking CSS, box model, Flexbox and matching the design). It explained concepts, gave me small tasks and helped me debug issues like a wrong file path and a misplaced property.

## Author

- Website - [Daniel Alves](https://daniel-alvesdev.com.br)
- GitHub - [@daniel-mscs](https://github.com/daniel-mscs)
- LinkedIn - [daniel-mscs](https://www.linkedin.com/in/daniel-mscs)