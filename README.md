# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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

- Build out the project to the designs provided

### Links

- Solution URL: [GitHub](https://github.com/pedrotpo/frontendmentor-profile-card)
- Live Site URL: [Github Pages](https://pedrotpo.github.io/frontendmentor-profile-card)

## My process

### Built with

- Semantic HTML5 markup
- SASS
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

CSS Positioning is a major pain in the ass. So it's important to understand how `relative` and `absolute` positioning work. Also, figuring out how to change the anchor point for positioning is a huge game changer.

```css
.some-component {
  transform:translate(-50%,-50%);
  position: absolute;
  top: 50%;
  left: 50%
}
```

In the above example, the component will be set to the exact center of the screen because a) due to the `position: absolute;` part of the code, the div will be positioned relative to its parent element with an absolute position (in case there is no parent element with absolute positioning, the element will use the body as the element to calculate its positioning), and b) due to the use of the `transform:translate(-50%,-50%);` property, which will set the anchor point of the element to its center.

### Continued development

CSS Grids are not something I usually work with on a daily, but it should. Its a powerfull tool, and can be very useful in situations where the design grid follows a somewhat rigid composition.

### Useful resources

- [CSS Trick's Complete Guide to CSS Grids](https://css-tricks.com/snippets/css/complete-guide-grid/) - The Grid Properties section is a lifesaver.

## Author

- Frontend Mentor - [@pedrotpo](https://www.frontendmentor.io/profile/pedrotpo)
