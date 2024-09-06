# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)


## Overview


### Screenshot

![Screenshot](./screenshot.jpg)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: (https://omarhdez-218.github.io/blog-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- Mobile-first workflow
- [Tailwind CSS](https://tailwindcss.com/) - For styles


### What I learned


Learned how to use a ttf font from a saved file within my directory using @font-face instead of importing it with a url via @import,
```css
@font-face {
    font-family: Figtree;
    src: url(./assets/fonts/Figtree-VariableFont_wght.ttf);
}
```
 A child element doesn't inherit parents background color by default, so i set all children elements background color to inherit,
```css

#container {
  background-color: white;
  ...
}

/* Now every child will have white as their background color */
#container * {
  background-color: inherit;
}

```


## Author

- Website - [Omar](https://github.com/Omarhdez-218)
- Frontend Mentor - [@Omarhdez-218](https://www.frontendmentor.io/profile/omarhdez-218)

