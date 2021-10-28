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
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview
Building a stats card component. Use of HTML and CSS only. Flexbox used to align the content.

### The challenge

Reversing the order of the columns shown.
- Desktop screens have a two column layout with the image on the right.
- Mobile screens have a single column layout with the image on the top.
- Method used > flex-direction : column-reverse;

### Screenshot

![](./screenshot.png)


### Links

- Solution URL: [https://github.com/sarojgurung/Stats-Card]
- Live Site URL: [https://sarojgurung.github.io/Stats-Card/]

## My process

The approach lately has been to do everything as fast as I can with the idea to do more. There without using any library, I gave class names to almost all the elements and styled accordingly.

Styling done with SCSS as that is what I am doing as a norm.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

'background-blend-mode' property which is probably brought from photo editing softwares and found the usage to be quite handy in this scenario.

Adjusting an element in the middle of the page is always something you have to google. 

```css
.img-container {
  background-blend-mode: multiply;
}
```

## Author

- Website - [Saroj Gurung](https://www.sarojgurung.com)
- Frontend Mentor - [@yourusername](hhttps://www.frontendmentor.io/profile/Sarojgurung1992)

## Acknowledgments

Thank you to Frontend mentor for this layout challenge.
