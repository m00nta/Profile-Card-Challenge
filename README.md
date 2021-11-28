# Frontend Mentor - Profile card component solution

This is My solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ).

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### Screenshot

#### Desktop

![](./screenshot.jpg)

#### Mobile

![](./screenshot1.jpg)

### Links

- Solution URL: [Add solution URL here](https://github.com/m00nta/Profile-Card-Challenge)
- Live Site URL: [Add live site URL here](https://m00nta.github.io/Profile-Card-Challenge/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

On this challenge I learned about adding multiple image to the background and how to position them with calc function.

```css
.body {
  background: url("./images/bg-pattern-top.svg"),
    url("./images/bg-pattern-bottom.svg") var(--Dark-cyan);
  background-position: calc(100% - 55vw) calc(100% - 40vh), calc(100% + 10vh) calc(
        100% + 31vw
      );
  background-repeat: no-repeat, no-repeat;
  background-size: contain, contain;
}
```

But I am not sure if this is the right or a good solution because it dosen't work perfect on mobile as you can see in the screenshot above.

### Continued development

I want to learn and understand "background image" in CSS and know how to position them well.

## Author

- Frontend Mentor - [@m00nta](https://www.frontendmentor.io/profile/m00nta)
- Twitter - [@m00nta](https://twitter.com/m00nta)
