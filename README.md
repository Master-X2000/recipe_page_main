# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Links

- Solution URL: [Add solution URL here](https://github.com/master-x2000/recipe_page_main/)
- Live Site URL: [Add live site URL here](https://master-x2000.github.io/recipe_page_main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid


### What I learned

Using the ::marker psudo selector, i was able to style the bullet for the unordered list as well as that for the ordered list.

```css
.section_two ::marker{
    color:var(--PREPARATION-TIME-CLR);
}

.section_three ::marker,
.section_four ::marker{
    color:var(--HEADING-CLR-900);
}
```

### Continued development

I will definetly keep working on how to edit and style my tables, since I used a display of grid fo style the table the way it was designed.

### Useful resources

- [Dave Gray List course](https://github.com/gitdagray/css_course) - This helped me for styling the bullet for the unordered list as well as that for the ordered list.

## Author

- Website - [Odezime Excel](https://github.com/master-x2000)
- Frontend Mentor - [@Master-x2000](https://www.frontendmentor.io/profile/master-x2000)
- Twitter - [@Excel Odezime](https://www.twitter.com/EOdezime66661)

## Acknowledgments

I was able to complete this challenge due to the help gotten from dave gray comprehensive CSS tutorial on lists.
