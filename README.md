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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![Desktop - version](./images/desktop_screenshot_solution_frontend_mentor_qr_code_component.png)
![Desktop - version](./images/desktop_alternative_screenshot_solution_frontend_mentor_qr_code_component.png)
![Mobile - version](./images/mobile_screenshot_solution_frontend_mentor_qr_code_component.png)
![Mobile - version](./images/mobile_alternative_screenshot_solution_frontend_mentor_qr_code_component.png)


### Links

- Solution URL: [Add solution URL here](https://github.com/ElijahOluwasegun/qr-code-component-main)
- Live Site URL: [Add live site URL here](https://elijaholuwasegun.github.io/qr-code-component-main/)

## My process
I started by creating the basic HTML structure.
### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- CSS Media queries
- [Styled Components](https://fonts.google.com/) - For font styles



### What I learned

First I used CSS display properties, specifically blocks and inherit. However, after studying more about CSS, I switched to flexbox.

To see how you can add code snippets, see below:

```css
.qr_sect {
    display: block;
    margin-top: 6.25em;
    margin-left: auto;
    margin-right: auto;
    padding-top: 0.625em;
    background-color: rgb(255, 255, 255);
    border: 0.75em;
    border-radius: 1.25em;
    width: 22%;
    height: 2500%;
}
```
```css 
.qr_sect {
    display: flex;
    flex-direction: column;
    justify-self: center;
    align-items:center;
    gap: 20px;
    padding-top: 0em;
    background-color: rgb(255, 255, 255);
    border: 0.75em;
    border-radius: 1.25em;
    width: 22%;
    height: 2500%;
}
```

### Continued development

Areas I would love to improve is writing good git commit messages. I would also love to properly grasp CSS flexbox especially when it comes to items, content and self.


### Useful resources

- [Mozilla](https://developer.mozilla.org/en-US/) - This helped me for CSS flexbox. I really liked the detailed information and clarity and will use it going forward.
- [TheOdinProject] (https://www.theodinproject.com/) - This helped me for everything, from HTML, CSS to understanding GIT, Github and linux installation.
- [W3schools](https://www.w3schools.com/) - This is an amazing resource which helped me to quickly understand the basics of HTML and CSS. I'd recommend it to anyone anxious to learn web development.
- [Example resource 1](https://nekocalc.com/px-to-percentage-converter) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.


**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@ElijahOluwasegun](https://www.frontendmentor.io/profile/ElijahOluwasegun)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
