# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). 

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
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview
- I was surprised at how difficult I found this challenge.
  - It started out really well until suddenly the white background on the card became a different color as did the background on the preparation section.
   - I pushed to the repository several times and, mostly, the published 
   site looked worse than the one in my browser.
   - Finally I viewed it on a different computer and it looked as I would have expected it to.
- Now I'll need to find out if some aspect of my browser is causing the problem

### Screenshot

![](./![recipe page](image.png))



### Links

- Solution URL: [Add solution URL here](https://github.com/MargM43/Recipe-page)
- Live Site URL: [Add live site URL here](https://resilient-meerkat-8e574b.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

- I learnt some really good new skills in this project:
  - the HTML for setting up a table;
  - how to use css Grid to style the different parts of a table and
  - the existence of, and how to use ::marker and .custom-marker
- Very, importantly, I found out how essential it is to test your code on a variety of different devices



```css
table {
    margin-block-start: 1.5rem;
    margin-inline-start: 2.3rem;
    @media (width <= 400px) {
        margin-inline-start: 0rem;
    }
}


tr {
    display: grid;
    grid-template-columns: 300px 1fr;
    padding-block-end: 2rem;
    @media (width <= 400px) {
        grid-template-columns: 150px 1fr;
    }
}

.custom-marker > li {
    padding-inline-start: 1rem;
}

::marker {
    font-weight: bold;
    color: var(--clr-Brown800);
}
```


### Continued development

-I plan to do a lot more work on pseudo elements and pseudo classes
- in conjunction with this, I'm also going to find out the finer details of ::before and ::after, especially in relation to formatting.
-I was not able to get the borders in the table working as per the design, so I plan to work on this also
- another focus area is going to be coding properly for accessability



### Useful resources

- [Example resource 1](https://www.youtube.com/watch?v=RmDh3m8b9cU) - Here I learned about the difference between pseudo classes and pseudo elements
- [Example resource 2](https://www.youtube.com/watch?v=xoRbkm8XgfQ&t=499s) - Until I saw this, I hadn't heard of the content property. I plan to find out more about this
- [Example resource 3](https://www.youtube.com/watch?v=sEcjwfQhbCs) - A few other handy little tricks for styling



### AI Collaboration

Describe how you used AI tools (if any) during this project. This helps demonstrate your ability to work effectively with AI assistants.

- What tools did you use (e.g., ChatGPT, Claude, GitHub Copilot)?
- How did you use them (e.g., debugging, generating boilerplate, brainstorming solutions)?
- What worked well? What didn't?



## Author

- Website - [Marg Gray](https://www.your-site.com)
- Frontend Mentor - [@yMargM43](https://www.frontendmentor.io/profile/MargM43)


## Acknowledgments

As usual, Kevin Powell has been a great help. Other people on Discord who helped me this time are Kapteyn Universe  and mr_machooo(I don't know how I should format this) and 