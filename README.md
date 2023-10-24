# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
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

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](./images/Mobile%20Solution.PNG)
The above links to a mobile view solution for the project.

![](./images/Desktop%20Solution.png)
The above links to a desktop view solution for the project.


## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- CSS Grid
- Mobile-first workflow
- CSS Pseudo-classes selectors only
- JavaScript (While this project doesn't require JavaScript, I decided to add it to give the project an extra functionality.)


### What I learned

- I go to try out the CSS _:not()_ Pseudo-Class.

```css
section:not(:first-child) {
    color: var(--Light-Gray);
}
```
- I was able to make use of JavaScript to give some dynamism to page by making the button toggle some CSS styles.
- I started this project with the mind of not working with classes or IDs but with the intention of only working only with pseudo-classes.
...When i got to using _media query_ for the desktop view, i discovered working with a display of _flex_ would cause some problems for me. I thought long and hard for a solution that would require me not using _flex_ or even position till i finally thought of using _Grid_ display.
...This has been a blessing.
- I got to further understand better why it is preferable to use relative length units in CSS like _rem_ as opposed to using absolute length units like _px_. Using rem and em made my page more responsive when i increased my browser's font-size from medium which is the recommended to very large or decreased it to very small. Using px had texts pushing out from their respective section elements.
- I love that i was able to use _grid_ to layout my _section_ elements without having to create another element to house the last two _section_ elements inorder to use _flex_.

### Continued development

- I am still looking to improve my use & understanding of semantic HTML elements. In this project i used 3 section elements inside of an article element since i couldn't see the page as been made of header, main and footer.
- I still intend to improve on my ability to write fewer lines of code while still maintaining full functionality.

### Useful resources

- [Link to Mr. Dave Gray's Youtube Channel](https://www.youtube.com/@DaveGrayTeachesCode) - His videos can turn you to a full stack web developer.
- [Link to Mr. Dave Gray's CSS Tutorial](https://www.youtube.com/watch?v=n4R2E7O-Ngo) - This is an 11hrs video that can help you understand CSS better. It is about 11hrs long. Take your time.
- [Link to freeCodeCamp Youtube page](https://www.youtube.com/@freecodecamp) - This is a rich repository of knowledge. I found Mr. Gray here.


## Author

- email address - [idemudiamahie23@gmail.com]
- Twitter - [@mahie_id](https://twitter.com/mahie_id)


## Acknowledgments

- My deepest appreciation goes to Mr. Dave Gray whose tutorial videos has helped build my foundation in web development.
- I am also grateful to GMT Software whose coding bootcamp has given me environment and community of like-minded individuals to grow.
