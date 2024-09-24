# Social-Links
Challenge from FrontendMentor to create a social links page 

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

### Screenshot

![](/Recipe-Page.png)

### Links
- Live Site URL: [https://melanie-cabriales.github.io/Social-Links/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I haven't started a coding project for a couple of months now so it was refreshing to reset my mind on how to approach the layout, design and components of this project to get the result I was looking for.

I was able to go in depth on the Flexbox documentation and understand how changing attributes can affect the output.

I had also never done media queries before so it was interesting to see how fixed values can affect the display of my website on different screen sizes and how to combat it so the UI looked aesthetically pleasing to keep viewers interested and keep it approachable.

In terms of code snippets I was proud of:

```css
 h2 + ul li::marker, h2 + ol li::marker{
    color: #8b6bc8;
   }
```
It was a fun challenge trying to figure out how to color code everything the way it was prompted in the challenge, I didnt realize I could group components like this or specify the marker to only be color coded

```css
    .image-size {
        border-radius: 15px;
        max-width: 100%; /* ensure the image fits within the container width*/ 
        height: auto; /* maintains aspect ratio */
        display: block; /* removes extra space below the image*/
        margin: 0 auto; /*centers the image if needed*/
    }
```
It was a struggle to adjust the image so it didnt take over the whole screen and it took some playing around with style elements to get it right.


### Continued development

<!-- Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect. -->

I think in the future I want to go more into the CSS documentation to add more elements and make the UI look more modern. 

Generally I want to make it a habit to go to the documentation first instead of searching up questions I have because then I can familiarize myself with the documentation and can problem solve faster.
 

### Useful resources

- [Resource 1](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_flexible_box_layout/Basic_concepts_of_flexbox) - This helped me understand how flexbox worked 
- [Resource 2](https://developer.mozilla.org/en-US/docs/Web/CSS) - This what I will be delving more into in the future.

## Author

- Frontend Mentor - [@Melanie-Cabriales](https://www.frontendmentor.io/profile/Melanie-Cabriales)

