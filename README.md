# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

-   [Overview](#overview)
    -   [The challenge](#the-challenge)
    -   [Screenshot](#screenshot)
    -   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
    -   [Useful resources](#useful-resources)
-   [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

-   View the optimal layout depending on their device's screen size
-   See hover and focus states for interactive elements

### Screenshot

![Screenshot](./screenshot.jpg)

### Links

-   Solution URL: [Frontend Mentor Challenge](https://your-solution-url.com)
-   Live Site URL: [Netlify - Product Preview Card Component](https://product-preview-card-component41.netlify.app/)

## My Process

### Built with

-   Semantic HTML5 markup
-   CSS custom properties
-   Flexbox
-   CSS Grid
-   Mobile-first workflow
-   Bootstrap 5

### What I learned

I was having some trouble with updating images depending on the screen size. I thought I'd need js for this. Then I found out about the picture tag. I saw that tag once before but I completely forgot about it because I never got to use that before. I saved me from writing js for this single feature. Hopefully I'll get to use this more often.

```html
<picture class="card-img-top">
	<source
		media="(min-width: 600px)"
		srcset="./images/image-product-desktop.jpg"
	/>
	<img
		class="rounded-1"
		style="width: 100%"
		src="./images/image-product-mobile.jpg"
	/>
</picture>
```

### Useful resources

-   [Bootstrap Components](https://www.bootstrap.com/components) - Really helpful when you are building components for your projects if you're using bootstrap.
-   [Bootstrap Utilities](https://www.bootstrap.com/utilities) - Very helpful for when you need to style in a specific way

## Author

-   Github - [Mahmudur Rashid](https://www.github.com/Mahmudur-Rashid)
-   Frontend Mentor - [@Mahmudur-Rashid](https://www.frontendmentor.io/profile/Mahmudur-Rashid)
