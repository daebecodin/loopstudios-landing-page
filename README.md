# Frontend Mentor - Loopstudios landing page solution

This is a solution to the [Loopstudios landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/loopstudios-landing-page-N88J5Onjw). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.


### Links

- Solution URL: [Add solution URL here](https://www.frontendmentor.io/solutions/loopstudios-lznding-page-swwlEiPhLP)
- Live Site URL: [Add live site URL here](https://daebecodin.github.io/loopstudios-landing-page/)

## My process
1. structured html
2. mobile css
3. mobile nav js
4. dektop css

### Built with
- HTML5 
- CSS 
- CSS Grid
- Mobile-first workflow


### What I learned
- I learned how important it is to structure your html before going to css.
- I alos learned that using root is very helpful when using custon fonts and colors
```html
<picture>
      <source
        media="(min-width: 850px)"
        srcset="images/desktop/image-hero.jpg"
      />
      <img id="mobile-hero" src="images/mobile/image-hero.jpg" alt="" />
    </picture>
```
```css
:root {
    /* colors*/
--white: hsl(0, 0%, 100%);
--black: hsl(0, 0%, 0%);
--dark-gray: hsl(0, 0%, 55%);
--very-dark-gray: hsl(0, 0%, 41%);

/* fonts*/
--font-type-1: "Josefin Sans", sans-serif;
--font-type-2: "Alata", sans-serif;
}
```
```js
open.addEventListener("click", () => {
  let navlist = document.getElementById("nav-list");
  navlist.style.transitionDuration = ".5s";
  navlist.style.marginTop = "0px";
  open.style.display = "none";
  close.style.display = "block";
});

close.addEventListener("click", () => {
  let navlist = document.getElementById("nav-list");
  navlist.style.marginTop = "-2000px";
  close.style.display = "none";
  open.style.display = "block";
});
```



### Continued development

I want to continur working of different screen sizes for this project

## Author

- Website - [Durand](https://www.your-site.com)
- Frontend Mentor - [@daebecodin](https://www.frontendmentor.io/profile/daebecodin)

