# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](/screenshots/Screen%20Shot%202023-03-20%20at%201.30.14%20PM.png)
![](/screenshots/Screen%20Shot%202023-03-20%20at%201.29.07%20PM.png)
![](/screenshots/Screen%20Shot%202023-03-20%20at%201.29.21%20PM.png)
![](/screenshots/Screen%20Shot%202023-03-20%20at%201.29.31%20PM.png)

### Links

- Solution URL: [Github](https://github.com/benedicklat/order-summary-component)
- Live Site URL: [Github](https://benedicklat.github.io/order-summary-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Bootstrap CSS
- CSS Grid

### What I learned

- Continuously building of html and css.

To see how you can add code snippets, see below:

```html
<div class="container position-relative shadow p-0 mb-5 bg-body rounded-4 m-auto mt-5" style="width: 420px; height: 650px;">
        <img src="images/illustration-hero.svg" class="illustration" style="width: 420px;" alt="">
            <div class="title">Order Summary</div>
              <div class="paragraph">You can now listen to millions of songs, audiobooks, and podcasts on any device anywhere you like!</div>
              
              <div class="row position-relative w-75 rounded-4 m-auto" style="background-color: hsla(226, 55%, 86%, 0.286);">
                <div class="col-2 pt-3">
                  <img src="images/icon-music.svg"  alt="">
                </div>
                
                <div class="col">
                  <p class="select"><strong>Annual Plan</strong>  $59.99/year</p>                 
                </div>
                
                <div class="col">
                  <button type="button" class="btn btn-link" style="font-family: 'Red Hat Display', sans-serif; font-weight: 700; color: hsl(245, 75%, 52%)" href="">Change</button>
                </div>
              </div>

              
              <button class="btn shadow p-2 mb-4 text-white" type="button" style="font-family: 'Red Hat Display', sans-serif; margin-left: 55px; margin-top: 35px; width: 74%; height: 50px; background-color: hsl(245, 75%, 52%);">
                Proceed to Payment</button>
              
              <div class="cancellation">
                <button type="button">Cancel Order</button>
              </div>
    </div>
```
```css
body {
    background-image: url(/images/pattern-background-desktop.svg);
    background-repeat: no-repeat;
    background-color: hsl(225, 100%, 94%);
    background-size: contain;
}
```


## Author

- Website - [John Benedick Lat](https://jbenedicklat.my.canva.site/)
- Frontend Mentor - [@benedicklat](https://www.frontendmentor.io/profile/benedicklat)
- Twitter - [@benedicklat](https://twitter.com/benedick_lat)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**


