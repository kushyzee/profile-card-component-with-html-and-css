# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

- Build out the project to the designs provided

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Learnt how to use flexbox to center an element vertically. I knew about this technique before now and i have tried using it on several occasions but only horizontal centering seem to work. Even when i gave the same value as the width to height (usually in %), the element never get centered vertically. In this project, i experimented with giving the flex container (in this case the body element) an height of 100vh (i usually use 100%) and the vertical centering worked! 😁 see code below

```css
body {
    font-size: 1.6rem;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center; /* center vertically */
}
```

and also figuring out how to properly position the profile pic was stressful, but then i saw online that you can use a negative border value to push elements outside their container (shocker) 😎

```css
img {
    margin-bottom: -5rem;
}
```

I never knew the below code will work and when it did, i was like "wow!"

```css
.profile-stats>div>p {
    color: rgb(150,150,150);
}

```

Don't even get me started on that calculations on the background-position property 😂 it was done by [@ApplePieGiraffe](https://www.frontendmentor.io/profile/ApplePieGiraffe)

### Useful resources

- [freecodecamp how to center anything](https://www.freecodecamp.org/news/how-to-center-anything-with-css-align-a-div-text-and-more/amp/) - I was always referencing them for info on how to center elements vertically, glad it finally paid off.

- I also caught up on a couple things from these guys - [ccs-tricks.com](https://css-tricks.com/quick-css-trick-how-to-center-an-object-exactly-in-the-center/)


## Author

- Frontend Mentor - [@kushyzee](https://www.frontendmentor.io/profile/kushyzee)


- Adios 👋