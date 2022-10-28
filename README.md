# 3-col-preview-card
Another Frontend Mentor challenge using only CSS and HTML (and a tiny bit of bootstrap)
# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout depending on their device's screen size [X]
- See hover states for interactive elements [X]

### Screenshot

![](./desktopview.jpg)
![](./desktopview_activestate.jpg)


## My process

- Applying the simple HTML tags
- identifying the colours for the cards
- applying the other relevant styles from google fonts
- applying tags to all the pieces
- styling for general style and then refining on smaller and smaller details
- applying button behaviour
- continuing refinement, especially when viewing on different viewports
- polishing and debugging


### Built with

- A tiny bit of bootstrap (but not really)
- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow (heavy consideration on tablet view as well, but failed)


### What I learned

```html
<h1>Some HTML code I'm proud of</h1>
```
<!-- <div class="row content">  
  <div class="col-lg-4 col-md-6 sedan-card">
    <svg width="64" height="40" xmlns="http://www.w3.org/2000/svg">there is an icon here, I promise</svg>
    <h1 class="sedan-h1">SEDANS</h1>
      <p>Choose a sedan for its affordability and excellent fuel economy. Ideal for cruising in the city 
      or on your next road trip.</p>
    <button class="btn sedan-btn">Learn More</button>
  </div>
-->

  Being able to use the 'row' and 'col' properties effectively to align all the content properly was pretty huge for me.

CSS
```
I am happy with the below CSS because I had just learning media queries in my bootcamp and was able to apply it well to 
this project. I could only to it to a mobile view and am still testing to figure out how to apply it to a tablet view.

@media (max-width: 1000px) {

    .sedan-card {
        border-radius: 3% 3% 0 0;
}

    .luxury-card {
        border-radius: 0 0 3% 3%;
    }

}

This padding amount seems to be the magic numbers to center things on desktop. So I will enshrine it here for all eternity.

.content {
    /*padding centers the whole contents */
    padding: 7% 15%;   
}


### Continued development

As stated before, I just started learning media queries and will work to figure out how to make websites mobile and tablet focused FIRST,
as more internet is being viewed on smaller ports than ever before.

I will also try and delve more into screen reader assistance and make the internet continually more accessible.

### Useful resources

My bootcamp on Udemy! [https://www.udemy.com/course/the-complete-web-development-bootcamp/]


## Author

- Frontend Mentor - [@Azulio123](https://www.frontendmentor.io/profile/Azulio123)



## Acknowledgments

My husband helped a bit, of course. Searching around on the internet, in particular a few great CSS websites helped. The resources given fromy my last challenge were also quite valuable. :3
