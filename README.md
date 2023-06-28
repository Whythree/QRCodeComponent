# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)



## Overview

### Screenshot

(./images/screenshots)


### Links

- Solution URL: https://github.com/Whythree/QRCodeComponent
- Live Site URL: https://whythree.github.io/QRCodeComponent/

## My process
I started by looking at the design and what elements I woudl need. After that I marked them up in HTML and created and linked to a stylesheet. I also linked the needed Font. 

In the stylsheet  first imported a CSS Reset after which I create the main container for the images and text. I centered the container and styled it and the image. 
After that I continued styling the h1 and p element.
### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

I struggled with getting the element centered, since I was not aware, that justify-content and align-items affect the children of the container it is used on. So at first I was trying to use these declarations on the items inside the container. After I went one up in the hierarchy and applied it to the body it worked. 

```
body{
    background-color:hsl(212, 45%, 89%) ;
    display: flex;
    justify-content: center;
    align-items: center;
    font-family: "Outfit";
    flex-direction: column;

    }
```

  I also learned, that you have to use rem units on everything font, otherwise the site can break should the user have adjusted his font size settings in the browser.   

  
### Continued development

For my next projects I want to continue getting comfortable using CSS and getting the Layouts I want. I want to broaden my knowledge and also want to be more comfortable in using declarations


### Useful resources

- [CSS Reset](https://gist.github.com/Asjas/4b0736108d56197fce0ec9068145b421) - This helped me getting a blank canvas and also provided some small quality of life things, that I tend to forget about like border-box reason.
- [Example Solution](https://www.frontendmentor.io/solutions/qrcode-solution-with-explanation-0LCmcOmbrj) This example helped me reappraoch this project. After I completed it initially I dove into code made by others and quickly realized that my solution was wrong. I only skimmed the code, because I didn't want to spoil myself, but it helped.
- [Font-Size never in Pixel] (https://fedmentor.dev/posts/font-size-px/) 
A helpful article on why font properties shouldnt be in pixels


## Author


- Frontend Mentor - [@Whythree](https://www.frontendmentor.io/profile/Whythree)



