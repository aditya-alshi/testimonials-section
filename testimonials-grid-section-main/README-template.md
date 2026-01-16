# Testimonials grid section solution

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

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![Desktop - 1440](./other-photos/1440.png)
![Laptop - 1024](./other-photos/1024.png)
![Mobile phone - 375](./other-photos/375.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learnt about grid-template-areas. Used it for the first time

```css
    grid-template-columns: repeat(3, minmax(min-content, auto));
    grid-template-areas:
      "one one two"
      "three four four"
      "five five five";
```

Learnt the difference between ```minmax(0, auto)``` and ```minmax(min-content, auto)```
Which I used for seperate media queries

```css 
    grid-template-columns: repeat(4, minmax(0, auto));
    grid-template-areas:
      "one one two five"
      "three four four five";
```

I learnt why grid-template-areas was a better approch than grid-template-rows and columns
### Continued development

- I think I need to dig deeper into css grid and flexbox.
- Also, I need to improve my sense for shadows and font-sizes. 
- Moreover I need to add focus on writing responsive fonts using css. 

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

## Acknowledgments

- [@z-khutsishvili](https://www.frontendmentor.io/solutions/testimonials-grid-section-taxy5qNhS_) solution had use of grid-template-areas which inspired me to use it in my project
