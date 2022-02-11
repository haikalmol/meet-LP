# Frontend Mentor - Meet landing page solution

This is a solution to the [Meet landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/meet-landing-page-rbTDS6OUR). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Meet landing page solution](#frontend-mentor---meet-landing-page-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
      - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
      - [Desktop (1440px)](#desktop-1440px)
      - [Tablet (768px)](#tablet-768px)
      - [Mobile (375px)](#mobile-375px)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
    - [Useful resources](#useful-resources)
  - [Author](#author)


## Overview

#### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

Here are the landing page screenshots : 

#### Desktop (1440px)

![](./starter-code/assets/img/screenshots/desktop.png)

________________________________________________


#### Tablet (768px)

![](./starter-code/assets/img/screenshots/tablet.png)

_________________________________________________

#### Mobile (375px)

![](./starter-code/assets/img/screenshots/mobile.png)

____________________________________

### Links

- Solution URL: [Click here](https://www.frontendmentor.io/solutions/responsive-landing-page-meet-html-css-Q68U52NnS)
- Live Site URL: [Click here](https://meet-landing-page-vert.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [Sass](https://sass-lang.com/) - Sass Preprocessor script language


### What I learned

I learned during this challenge to structure the scss files to find my way around and I also improved on the interpretation of the model.

Before I didn't know how to put the color with an opacity on top of an image background.



I put the background image in addition to background color and then use :
```css  
background-blend-mode: multiply; 
```
to make the background image blend with the background color, but the rendering is not the same as on the mockup.
 

Now I used the method Use of CSS pseudo-elements which allows to use the :before of an element which contains a background image to put on top of it a background in color with opacity.

it's thanks to a tutorial that I could find this trick I put the link in the "Useful resources" section.


### Continued development

When I was at the point of completing this challenge, I noticed that I was repeating media queries giving maximum and minimum sizes to each scss file and that I normally had to use variables to change the max and min widths.

the next challenge is to improve myself in **sass** and again on the **html & css** structure because still I find that I use too much margin and padding to space while there is the flex with gap 




### Useful resources

- [How to Change a CSS Background Image’s Opacity](https://www.digitalocean.com/community/tutorials/how-to-change-a-css-background-images-opacity) - This helped to change a css Background Image opacity : this is what helped me to put a colored background with opacity over a background image 



## Author

- Website - [hadysane.tech](http://hadysane.tech/)
- Frontend Mentor - [@hadysane](https://www.frontendmentor.io/profile/hadysane)
- Twitter - [@HadySane](https://twitter.com/HadySane)


