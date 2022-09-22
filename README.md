# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### Screenshot

![](./dist/assets/images/screenshot.jpg)


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
- Sass
- [Sass Boilerplate](https://github.com/KittyGiraudel/sass-boilerplate) - Sass module system


### What I learned

In this project I applied using the normalize.scss file which resets all default browser styles. I also applied the background:

To see how you can add code snippets, see below:

```html
<div class="card__img">
        <div class="card__img--overlay"></div>
        <picture>
          <source media="(min-width:720px)" 
                  srcset="./assets/images/image-header-desktop.jpg" 
                  type="image/">
          <img src="./assets/images/image-header-mobile.jpg" alt="Office">
        </picture>
</div>
```
```css
.card__img--overlay {
  background-color: hsla(277, 100%, 35.3%, 0.67);
  background-blend-mode: multiply;
}
```

### Continued development

On to the next projects I will still continue to fix my previous designs. In my next project, Im gonna try to build it with better accessibility.  



### Useful resources

- [Sass Boilerplate](https://github.com/KittyGiraudel/sass-boilerplate) - This helped me to build my own boilerplate since this is still using the @import.

## Author

- LinekdIn - [John Lois Floro](https://www.linkedin.com/in/jlfloro/)
- Frontend Mentor - [@loifloro](https://www.frontendmentor.io/profile/loifloro)
- Twitter - [@loisfloro](https://www.twitter.com/@loisfloro)
- Github - [loifloro](https://github.com/loifloro)

