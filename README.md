# QR code component solution

This is a solution to the QR code component.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### Screenshot

![](./screenshot/Screenshot%20QR%20Code%20Component.pngscreenshot.jpg)


### Links

- Solution URL: https://github.com/GitHubPaulPP/qr-code 
- Live Site URL: https://githubpaulpp.github.io/qr-code/

## My process
1. Looking through the designs to start planning the project.
2. Structuring content with HTML. 
3. Writing out the styles for the project and adding styles from the top on down. 
4. Debugging.
4. Deploying the completed project. 

### Built with

- HTML5 markup
- CSS 
- Flexbox
- Mobile-first workflow

### What I learned

1. Height of the element is very important! Elements are only as high as the content within them. If the content is not tall enough, these elements won't cover the entire height of the browser window. Setting the height of the flex container to 100% of the viewport ensures that they will stretch to the full available height allowing for a reference height to center its contents.  The min-height: 100vh CSS property is used to ensure that the .container will have a minimum height of 100% of the viewport height (vh). 
2. The interplay between width and max-width, they work in tandem for responsiveness: fixed max-width in px ensures that the child element does not become too wide on larger containers, which can be important for maintaining readability and aesthetic appeal. Width of 100% - on smaller containers (or screens), the child element will shrink to fit the container's width, maintaining the layout's fluidity and responsiveness.  
3. There is no single way to complete this project. At least 3 ways are available depending on what you decide to use: media queries, flexbox, grid.     


### Useful resources

- [MDN Mozilla](https://developer.mozilla.org/en-US/docs/Learn).

## Author

- Website - [Paul PP](https://github.com/GitHubPaulPP/qr-code)

