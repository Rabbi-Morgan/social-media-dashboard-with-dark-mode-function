# Frontend Mentor - Social media dashboard with theme switcher solution

This is a solution to the [Social media dashboard with theme switcher challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-media-dashboard-with-theme-switcher-6oY8ozp_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

This a social media dashboard with a button to toggle between the light and dark mode.

### Screenshot

![](./screenshot.jpg)

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it.

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

The header was created with a destop first approach, but the main content was a created with css grid and it made it responsive.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Destop first workflow

### What I learned

First of all I leant that when you display a container as flex, although it makes it a flexbox but it all make in an inline-block...

furthermore I noticed that the mobile first rule doesn't work for all projects and for headers and navigations, the mobile first rule doesn't apply.

it also happened that I used the filter property for the first time and it was a good property to use.

```css
.btm_cards:hover,
.cards:hover {
  /* the filter brightness is the original style but I'll prefer the drop-shadow */

  /* filter: brightness(125%); */
  filter: drop-shadow(0px 0px 7px rgba(0, 0, 0, 0.2));
  cursor: pointer;
}
```

### Continued development

I would love to add other funtionalities to the interface so it will be a complete web applicaion.

## Author

- Website - [Omobolaji Anuoluwapo Faruq](https://www.your-site.com)
- Frontend Mentor - [@morgan](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@anuoluwapo6](https://www.twitter.com/yourusername)

## Acknowledgments

Well, I saw a tutorial video on css grid in other to use the property in this challenge and a video to set the dark theme functionality.
