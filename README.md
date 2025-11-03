# Frontend Mentor - Product preview card component

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 


## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

Fairly simple challenge that I will use to explore concepts that are not so simple to me at this point. Clamped scaling fonts, mobile-first design, and a scss--oh my!

### Screenshot

<img src="./images/Desktop_Screenshot.png" width="600">

## My process

I will be starting with a mobile-first approach to this project and build out the mobile design before shifting to accomodate the desktop view. Don't anticipate too much trouble with this project nor will I particularly emphasize any pixel perfect goalset here, as last project was quite time consuming for it and this is largely review at this time.

Ideally I would like to leverage some of the skills being taught in this course. First, I have mixed messaging on setting font to 62.5% to make for simple rems. Some say do it, some say it impact people with accessibility issues. I'm going to err on the side of caution and assume that this truly does impact people with accessibility limitations and I will bite the bullet and just do my 1.6 math the old fashioned way like the pioneers. 

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

Top source of new experience was the `<picture>` tag and its role in logic-based delivery purely in html. Was not aware of this capacity in the markup language and found it really neat to work with, albeit I want more practice.

### Continued development

Update - 11/3/25: Based on feedback, modified with internal font resources with preload values included to prevent flash of unstyled text, added more BEM-aligned classes to tags, and began exploring clamp mechanics for both font and margins. Mobile scaled down to support for 17.5rem vw. 

## Author

- Frontend Mentor - [@MalakDynamics](https://www.frontendmentor.io/profile/MalakDynamics)

## Acknowledgments

Thanks to Frontend Mentor for all the assets and practice projects!
