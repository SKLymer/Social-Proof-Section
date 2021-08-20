# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the section depending on their device's screen size

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

Started with the desktop first. I'll try to go mobile first on the next challenge. Initially used inline block on the Heading and Ratings section,
just to diversify my methods and familiarize myself with differnt properties.

I couldn't get the elements aligned on the edge of the container initially and I think that's why i shifted to flex.

After the header i focused on the ratings section which was fairly easy. I tried rto use margin initially for the staggered displacement effect. But the background was stretching for some reason, I'm not sure if this was the cascading margins causing this, oh no I jjust remembered that the background strecthed when I used the left property as well, even after I changed the positioning. 

I ended up using transform and translate to create the effect without affecting the background.

In the testimonials I used Grid more diversification, and it was fairly simple. 

I have to think about naming my classes better. And differentiating what to class and what to use compound selectors on.


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid


### What I learned

Familiarized myself with the repeat autofill and minmax functions. I was getting an error initially, due invalid values.

```css
.testimonials {
    
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(300px, 1fr));
    font-weight: 500;
    grid-gap: 1.75em;
    height: 110%;
}

```

### Continued development

-Study that strectched background with the use of margin or left
-Complexed Grid template values.

