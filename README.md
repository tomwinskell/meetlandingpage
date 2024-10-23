# Frontend Mentor - Meet landing page solution

This is a solution to the [Meet landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/meet-landing-page-rbTDS6OUR). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![screenshot-desktop](https://raw.githubusercontent.com/tomwinskell/meetlandingpage/refs/heads/main/assets/screenshots/screenshot-desktop.png)
![screenshot-tablet](https://raw.githubusercontent.com/tomwinskell/meetlandingpage/refs/heads/main/assets/screenshots/screenshot-tablet.png)

### Links

- Solution URL: [https://github.com/tomwinskell/meetlandingpage](https://github.com/tomwinskell/meetlandingpage)
- Live Site URL: [https://tomwinskell.github.io/meetlandingpage](https://tomwinskell.github.io/meetlandingpage)

## My process

### Built with

- Bootstrap 5.3
- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- BEM

### What I learned

- Wow, what a journey. This took me longer than expected but I wanted to work with Bootstrap.
- I like working mostly in the html file, it saves a lot of switching back and forth between html and css. I think it would be a lot quicker once you know all of the class names and intricacies of Bootstrap.
- This layout was relatively challenging because of the differences between layouts for the screen sizes. That took a lot more time than I anticipated.
- Figured out that CSS Grid can be used to effectively overlay items. I really enjoyed doing that. I wrote a blog post about it. [http://tomwinskell.simple.ink/](https://tomwinskell.simple.ink/overlay-elements-with-css-grid-122eebbfd13f80f09bafe3492f9a942b)

Here's a code snipet for the overlay footer. Screenshot below also.

```css
.footer {
  display: grid;
  grid-template-rows: auto 28px 1fr;
  grid-template-columns: 1fr 1fr 1fr;
}

.footer__divider {
  grid-area: 1 / 2 / 3 / 3;
  align-self: end;
  z-index: 1;
}

.footer__container {
  grid-area: 2 / 1 / 4 / 4;
}
```

![screenshot-footer](https://raw.githubusercontent.com/tomwinskell/meetlandingpage/refs/heads/main/assets/screenshots/screenshot-footer.png)


### Continued development

- BEM
- CSS Grid
- [OOCSS](https://github.com/stubbornella/oocss/wiki)
- Bootstrap

### Useful resources

- [MindBEMding – getting your head ’round BEM syntax](https://csswizardry.com/2013/01/mindbemding-getting-your-head-round-bem-syntax/)
- [About HTML semantics and front-end architecture](https://nicolasgallagher.com/about-html-semantics-front-end-architecture/)
- [BEM — is a methodology that helps you to create reusable components and code sharing in front‑end development](https://getbem.com/)
- [CSS Grid Layout Guide](https://css-tricks.com/snippets/css/complete-guide-grid/)
