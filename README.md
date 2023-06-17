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
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](./images/screenshot.jpg)


### Links

- Solution URL: (https://github.com/Nikkaburger/order-summary-component-main)
- Live Site URL: (https://resplendent-trifle-0aab73.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

I learnt about setting background images as body of webpage. I also learnt about using flexbox and media query for mobile responsive design

```html
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" href="images/favicon-32x32.png">
    <link rel="stylesheet" href="css/style.css">
    <title>Order Summary Component Main</title>
</head>
<body>
    <div class="container">
        <img src="images/illustration-hero.svg" class="imagebox">
        <div class="description">
            <h1>Order Summary</h1>
            <p> You can now listen to millions of songs, audiobooks, and podcasts on any device anywhere you like!</p>
            <div class="pricebox">
                <img src="images/icon-music.svg" class="circle">
                <div class="pricing">
                <div class="plan">Annual Plan</div>
                <div class="price">$59.99/year</div>
                </div>
                <div class="option">change</div>
            </div>
            <button type="button" class="button">Proceed to Payment</button>
            <p>Cancel Order</p>
        </div>
    </div> 
</body>
</html>
```
```css
html, body{
    background-image: url('/images/pattern-background-mobile.svg');
    background-repeat: no-repeat;
    background-position: center center;
    background-size: cover;
    font-family: 'Red Hat Display', sans-serif;
    font-size: 16px;
    margin: auto;
    background-color: hsl(225, 100%, 94%);
    justify-content: center;
    align-items: center;
    display: flex;
    overflow: hidden;
}

.container {
    width: 350px;
    height: 550px;
    justify-content: center;
    align-items: center;
    margin: 55px 20px;
    border-radius: 15px;
    background-color: hsl(0, 0%, 100%);
}

.description {
    width: 300px;
    height: 100%;
    font-family: 'Red Hat Display', sans-serif;
    padding: 10px 20px;
    margin: 0px;
    border-bottom-right-radius: 15px;
    border-bottom-left-radius: 15px;
    justify-content: center;
    align-items: center;
}

.imagebox {
    width: 100%;
    height: 180px;
    margin: 0px;
    border-top-right-radius: 15px;
    border-top-left-radius: 15px;
}

h1 {
    font-size: 26px;
    font-weight: 900;
    text-align: center;
    font-family: 'Red Hat Display', sans-serif;
}

p {
    font-size: 16px;
    font-family: 'Red Hat Display', sans-serif;
    font-weight: 500;
    color: hsl(224, 23%, 55%);
    text-align: center;
    justify-content: center;
    align-items: center;
}

.pricebox {
    border-radius: 15px;
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    background-color: hsl(225, 100%, 98%);
    width: 290px;
    height: 75px;
    padding: 5px;
}

.pricing {
    flex-direction: column;
    display: flex;
    margin-left: 20px;
}

.circle {
    float: left;
}

.plan {
    font-weight: 900;
    font-family: 'Red Hat Display', sans-serif;
    font-size: 16px;
    color: black;
    flex-direction: column;
}

.price {
    font-size: 14px;
    font-weight: 800;
    color: hsl(224, 23%, 55%);
    flex-direction: column;
}

.option {
    margin-left: 60px;
    text-decoration: underline;
    font-size: 16px;
    font-weight: 700;
    color: hsl(245, 75%, 52%);
}

.button {
    margin-top: 20px;
    font-size: 16px;
    padding: 15px 50px;
    font-weight: 700;
    width: 300px;
    background-color: hsl(245, 75%, 52%);
    color: hsl(0, 0%, 100%);
    border-radius: 10px;
    border-width: 0px;
    justify-content: center;
    align-items: center;
}
```


### Continued development

My focus is on mastering modern web design techniques through continuous learning, experimentation, and a willingness to adapt to the ever-changing web landscape. 
By focusing on responsive design using, HTML5, CSS3, JavaScript, and PHP, to be adequately equipped to create visually stunning and user-friendly websites. Embrace new technologies, stay curious, and push the boundaries of my creativity to unlock endless possibilities in the world of web development. 

### Useful resources

- [#CSSMediaQuery](https://courses.webdevsimplified.com) - This helped me to understand and fix media query for the mobile version of my design, the tutorial was direct and explanatory. I really liked this pattern and will use it going forward.
- [#HTMLFullCourseforBeginners](https://courses.davegray.codes/) - This is an amazing course which helped me finally understand the functionality of #HTML5 tags. I'd recommend it to anyone still learning this concept.
-[#CSSTutorialFullCourseforBeginners](https://courses.davegray.codes/) - This is an amazing course which helped me finally understand CSS tags, syntax and their functionalities. I'd recommend it to anyone still learning this concept.

## Author

- Website - [Oluwaseun Akeju](https://www.fluxverge.com)
- Frontend Mentor - [@nikkaburger](https://www.frontendmentor.io/profile/nikkaburger)
- Twitter - [@fluxverge](https://www.twitter.com/fluxverge)

## Acknowledgments

Special thanks to Almighty God for the completion of this task, my profound gratitude to Dave Gray, Omolade Sunday, Akinola Akeem and Webdevsimplified for their immense contributions.
