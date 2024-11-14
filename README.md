# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm).

## Table of contents

- [Overview](#overview)
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

### Screenshot

![](./screenshot.gif)

### Links

- Solution URL: [Github link](https://github.com/snigdha-sukun/recipe-page)
- Live Site URL: [Recipe Page](https://recipe-page-livid-xi.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS

### What I learned

I learned how to use font url

```css
@import url('https://fonts.googleapis.com/css2?family=Outfit:wght@100..900&family=Young+Serif&display=swap');
```

I learned how to set & use variables

```css
:root{
    --white: hsl(0, 0%, 100%);
    --stone-100: hsl(30, 54%, 90%);
    --stone-150: hsl(30, 18%, 87%);
    --stone-600: hsl(30, 10%, 34%);
    --stone-900: hsl(24, 5%, 18%);
    --brown: hsl(14, 45%, 36%);
    --rose-800: hsl(332, 51%, 32%);
    --rose-50: hsl(330, 100%, 98%);
    --header-font: "Young Serif", serif;
    --body-font: "Outfit", sans-serif;
}
```

I learned how to change the color of `<hr>` tag

```css
hr {
    background-color: var(--stone-150);
    border: none;
    height: 1px;
}
```

I learned how to make the numbers in `<ol>` bold
```css
ol > li::marker {
  font-weight: bold;
}
```

### Continued development

I still need to practice the positioning an element more. I also need to learn about CSS in general & HTML5 rules.

### Useful resources

- [Change the color of `<hr>`](https://www.tutorialrepublic.com/faq/how-to-change-the-color-of-an-hr-element-using-css.php) - This helped me for change the color of `<hr>`.
- [Make numbers bold in `<ol>`](https://stackoverflow.com/a/57660865) - This helped me to make the numbers in `<ol>` bold.

## Author

- Frontend Mentor - [@snigdha-sukun](https://www.frontendmentor.io/profile/snigdha-sukun)

## Acknowledgments

I learned a lot about creating & using variables from this [github user](https://github.com/S-Alif).
