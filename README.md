# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./desktop-screenshot.jpg)
![](./mobile-screenshot.jpg)

### Links

- Solution URL:(https://github.com/MorganEJLA/product-preview-card-component-main)
- Live Site URL:(https://morganejla.github.io/product-preview-card-component-main/)

## My process

-This was a code-along with Kevin Powell's tutorial. I am using this as a jumping off point to code my other front end mentor projects using this same system without a tutorial. I am also keeping in mind writing up detailed README files.

### Built with

- Semantic HTML5 markup
- CSS Reset - Josh Comeau
- CSS custom properties
- Flex
- CSS Grid
- Mobile-first workflow
- locally scoped variables
- Accessible HTML

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<span class="sr_only">Original price: </span>
<p><s>$169.99</s></p>
```

```css
.sr_only:not(:focus):not(:active) {
  clip: rect(0 0 0 0);
  clip-path: inset(50%);
  height: 1px;
  overflow: hidden;
  position: absolute;
  white-space: nowrap;
  width: 1px;
}
```

### Continued development

Using pseudo elements and locally scoped CSS is something new for me but what I am getting used to. Also aggressive googling to find the code I need to do the thing I want to do (i.e. screen-reader code snippets). Im learning also to think more about screen readers and what can't be read by them and knowing when to implement sr-only code.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [CSS Reset-Josh Comeau](https://www.joshwcomeau.com/css/custom-css-reset/) - This is a good CSS Reset, that was used in this project.
- [Footer action](https://www.w3docs.com/snippets/css/how-to-create-sticky-footer-with-css.html) - I usually have issues with my footer and wanted a resource that could provide me with various examples of footers.

## Author

- Frontend Mentor - [@MorganEJLA](https://www.frontendmentor.io/profile/MorganEJLA)

## Acknowledgments

The CSS Evangelist Kevin Powell for teaching best practices in setting up html and css making the workflow cleaner and quicker!
