# Multilevel Dropdown

I try to build a multilevel dropdown menu and some forms. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- Hover over the navigation items and see the dropdown appear and again be able to do the same with the appeared items to make the corresponding side dropdown appear. 

### Screenshot

![](./screenshot.png)


### Links

- [Solution URL](https://github.com/geeky-amat/Multilevel-Dropdown)
- [Live Site URL](https://geeky-amat.github.io/Multilevel-Dropdown/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

- When I tried to insert an image of an indicator right arrow in front of the text in front of which the dropdown was to appear, the image would not push the container to grow in size unlike text and would end up being outside the anchor tag which the image was plced in. Still couldn't figure out the reason for the same but anyway this wasn't the right way to do it. It could probably have something to do with the images being replaced elements but anyway I'm not sure because it doesn't happen elsewhere. Finally I used the ::after seudo element to have the indicator right arrow.
- When I want to check if the input entered in an input field is a valid one using a Regex, should I do it inside the onChange handler or inside the useEffect hook? I ask this because when I log the input value using a state variable inside the onChange handler, it lags by one step but same doesn't happen when logging using the useEffect hook with proper dependencies provided.


### Continued development



## Author

- Frontend Mentor - [@geeky-amat](https://www.frontendmentor.io/profile/geeky-amat)

