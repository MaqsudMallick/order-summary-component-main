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


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: (https://github.com/MaqsudMallick/order-summary-component-main)
- Live Site URL: (https://maqsudmallick.github.io/order-summary-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

- padding shouldn't be used along with height or width css properties
- float propery wraps around anything and everything and shouldn't be used casually

```html
<p class="plan-description">
  <span>Annual Plan</span> <br />$59.99/year
</p>
<img src="images/icon-music.svg" alt="Music-icon" class="music">
<div class="change">
<a href="#">Change</a>
</div>
</div>
```

```css
.plan
{
  background-color: #f8f9fe;
  width: 350px;
  height: 100px;
  border-radius: 20px 20px 20px 20px;
  margin: 0 auto 0 auto;
  text-align: left;

}
.music{
  height: 48px;
  width: 48px;
  float: left;
  margin: 25px 0 25px 20px;
}
.plan-description
{
  color: #7d8399;

  margin: 30px 10px 25px 20px;
  display: inline-block;
  text-align: left;
}
.change
{

  float: right;
  margin: 40px 30px 0 0;
}
```

## Author

- Frontend Mentor - [@MaqsudMallick](https://www.frontendmentor.io/profile/MaqsudMallick)
