# Frontend Mentor - Ricky's Art gallery website solution

This is a solution to the [Art gallery website challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/art-gallery-website-yVdrZlxyA). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

I used CSS Grid and variables to create a responsive layout with a header, gallery grid, and footer that adapts to different screen sizes through media queries. This is combined with fixed sizes, background images, and flexible units to ensure the design remains presentable and functional on all devices.

This project took a lot longer than I anticipated (a recurring scenario with me), and that was due to scaling down the design while maintaining responsiveness, i.e., font size, container width, and height, and adjusting the CSS grid and flexbox layouts throughout the viewports. 

### The challenge

Users should be able to:

- View the optimal layout for each page depending on the device's screen size
- See hover states for all interactive elements throughout the site
- **Bonus**: Use [Leaflet JS](https://leafletjs.com/) to create an interactive location map with custom location pin

### Screenshot

<img src="./desktop home art gallery.png"/>
<img src="./tablet home art gallery.png"/>
<img src="./mobile home art gallery.png"/>
<img src="./desktop location art gallery.png"/>
<img src="./tablet location art gallery.png"/>
<img src="./mobile location art gallery.png"/>


### Links

- Live Site URL: 

## My process

- I structured my HTML semantically
I began by organizing key sections with semantic tags (<header>, <section>, <footer>). Use containers like <div>, <section>, or <figure> to group related content such as images, text, and buttons.
For better practice for SEO (Although I'm not so familiar with this yet). 


- I assigned unique class names
I created descriptive classes (.hero-section, .gallery-grid, .footer-container) for each section or element that needs styling. 
This makes targeting with CSS easier and more transparent.


- Layout planning
I decided how my layout will adapt to different screens. For example, my header might be a three-column grid, my gallery uses a grid with specific areas, and my footer content adjusts with media queries.


- Then, for CSS I added reset & variables
Set box-sizing: border-box, remove default margins, and define CSS variables for colors and sizes (:root {}) for consistency.


- I began styling major components
Apply CSS properties:

For the header: background-image, background-size, background-position, and height.

For content containers: use Grid or Flexbox for structure.

For images: set width: 100%, adjust object-fit if needed.

For text and buttons: set fonts, sizes, spacing, and hover effects.


- I added media queries for better responsiveness for desktop, tablet, and mobile viewports
Add breakpoints at common widths:

Grid columns/rows

Font sizes

Padding and margins

Display properties (block, flex, grid) for stacking content vertically


- I continue to test and fine-tune my media queries
I used the browser tools to resize and see how the layouts reacted. Adjust CSS properties like background-size, element sizes, or grid areas until my design felt smooth and consistent across devices.


- Summary: 

I started with clean HTML and meaningful classes. I planned layout with CSS Grid and Flexbox, then progressively refined it with media queries and testing. 

Focused on structure first, then style with responsiveness in mind.

### Built with

- Semantic HTML5 Markup
- Flexbox
- CSS Grid
- Desktop-first workflow

### What I learned

Initially, figuring out how to make the header's background image responsive was challenging. The image wasn’t scaling properly across different screen sizes, causing layout issues. After experimenting with background-size values (cover vs. contain), adjusting container heights, and analyzing how the image behaved on different devices, I learned to set background-position: center; and choose the right background-size to ensure the image filled the space accordingly without overflowing or losing quality. This process involved trial and error—testing different CSS properties, inspecting results in browser dev tools, and fine-tuning your sizes and positions until the header looked perfect on all screens.

- I experimented with background-size:
I tried background-size: cover, which is great for filling the entire header area, but on bigger screens, it zooms in and crops parts of the image, which becomes a hassle. 
Then, I tested background-size: contain, which kept the whole image visible without cropping but sometimes left empty space around it.


- I began adjusting the background-position:
I played with background-position: center, which kept the image focused in the middle and made it look more balanced as the screen size changed.

- I also tweaked the container height:
Initially, fixed heights caused the image to overflow or appear too small. I learned that using relative units like vh or flexible height helped the header adapt better. I also removed or set heights to auto to let the image naturally scale, which solved my issue. 

- Throughout the process, I used the browser dev tools:
I constantly inspected my code in the browser to see how the image behaved when resizing the window. I saw how different background-size and background-position values affected the look.

- Summary:

It was a simple trial and error. Through experimenting and observing, I discovered that combining background-size: cover with background-position: center and setting the header height to a flexible value like min-height: 80vh or a fixed px helped my header image look consistent and visually acceptable across devices.

## Useful resources

It was trial and error, and I didn't use any resources to finish this project, which took me 3 days—quality over Quantity. 


## Author

--Website: (https://www.rarroyoharo.com)<a href="https://www.rarroyoharo.com" target="_blank">rarroyoharo.com</a> 
--Frontend Mentor - [@RiickyRiick]<a href="https://www.frontendmentor.io/profile/RiickyRiick" target="_blank">@RiickyRiick</a> 


