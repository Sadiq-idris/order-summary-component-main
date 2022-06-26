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
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot
![Screen Shot 2022-06-26 at 09 16 27](https://user-images.githubusercontent.com/106121876/175828319-786b4407-c5c9-43cd-b4b7-fa06b30a1404.png)
![Screen Shot 2022-06-26 at 09 17 23](https://user-images.githubusercontent.com/106121876/175828334-69507437-900d-4b23-8119-a5a8baabda11.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [https://your-live-site-url.com](https://sadiq-idris-order-summary-component-main.pages.dev/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

i learn how to use flexbox with text and img together to make them inline element,it simple to make them inline element and aligning  them with flexbox is easy.
here is the sample of the code; 

```html
      <div class="plan">
          <img src="images/icon-music.svg" class="music" alt="">

          <div class="year">
            <h2>Annual Plan</h2>
            <span>$59.99/year</span>
          </div>
          <a href="#" class="change">Change</a>
      </div>
```
```css
.plan{
    display:flex;
    justify-content:space-around;
    align-items:center;
    margin:20px 0;
    background-color: hsl(225, 100%, 98%);
    padding:20px;
    border-radius:10px;
    width:100%;
}
```

## Author

- Website - [sadiq idris](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)


