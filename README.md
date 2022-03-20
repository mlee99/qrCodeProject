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
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![Desktop Image](https://github.com/mlee99/qrCodeProject/blob/main/images/screenshot-desktop.png)
![Mobile Image](https://github.com/mlee99/qrCodeProject/blob/main/images/screenshot-mobile.png)

### Links

- Solution URL: [QR Code Project](https://github.com/mlee99/qrCodeProject)

## My process

### Built with

- Semantic HTML5 markup
- CSS/Sass

### What I learned

I have a fairly introductory level of HTML and CSS, and going after this project allowed me to pracitce my re-structing of HTML/CSS topics such as:
  - Code organizational skills
  - Identifying different elements within HTML using IDs and classes
  - Understanding what variables are in comparison to those called in languages such as Python or VBA (which I'm a little more familiar with)
  - Mixins
  - Functions
  - Partial files ("_variables.scss")

Otehr topics that I learned during this project:
  - Utilizing shortcuts within an IDE
  - How to use an IDE and push/pull repositories from my local desktop to a public website
  - How to correctly link css/scss files to your master html file (I've only used platforms such as Codepen or W3)

While this code isn't particularly the most impressive, I learned how to use mixins and functions within the pre-processing language Sass:

```sass
'_functions.scss'
@function weight($weight-name) {
    @return map-get($font-weights, $weight-name);
}

@function font($font-style) {
    @return map-get($font-Family, $font-style);
}

'_mixin.scss'
@mixin centerPage {
    margin-left: auto;
    margin-right: auto;
    text-align: center;
}
```

### Continued development

Moving forward, this is what I'll consider as one of my "first" projects (at least with Front-end Mentor). I do have some website projects on CodePen following FreeCodeCamps curriculum. However, I believe while I was able to construct the websites from scratch, the majority of it was copying the sample/templates. I still struggled with them, but I feel as if I'm able to learn a lot more from this other projects with a "here's a final design, do it."

Ideally, I'd like to make about 10-15 more newbie projects so build my confidence with HTML, CSS, and JS and then move into larger projects (lines 200-500).

So, that being said, I am 1/15 for newbie projects!!

### Useful resources

- [Sass Tutorial for Beginners - CSS With Superpower](https://www.youtube.com/watch?v=_a5j7KoflTs&ab_channel=freeCodeCamp.org) - This helped my understand Sass and how I can use partial files to construct the main.scss file, which later trasnlates automatically into the main.css file. Variables, funcitons, mixins-- you name it. It can be all seperated and organized, which I believe will help in a much larger project with the assistance of a team.
- [W3 Schools](https://www.w3schools.com/) - Similar to FreeCodeCamp.org, but I was able to find speicifc topics such as "How to add a radius to a border" or any other topic you can think of. Their write-ups are easy to follow and can be impletemented into your own work. Type up any question that you may have and you'll be able to find it on the website.


## Author

- Frontend Mentor - [@mlee99](https://www.frontendmentor.io/profile/mlee99)

## Acknowledgments

Thank you to FreeCodeCamp, Youtube, and the creator of the Sass pre-processing language, Hampton Catlin.
