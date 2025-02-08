# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![Screenshot1](./images/Screenshot.png)
![Screenshot2](./images/Screenshot2.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [live site URL](https://sonnen99.github.io/Challenge-3-column-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Bootstrap for card design
- @media breakpoints
- Desktop-first workflow
- Refactoring


### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
    <div class="col col-lg-4 col-md-4 col-sm-12 col-xs-12">
      <div class="card sedan-card">
        <div class="card-body">
          <img src="images/icon-sedans.svg" alt="sedans" class="card-img-top icon">
          <h1 class="card-title">
            SEDANS
          </h1>
          <p class="card-text">
            Choose a sedan for its affordability and excellent fuel economy. Ideal for cruising in the city
            or on your next road trip.
          </p>
          <button class="btn btn-light sedan-btn">Learn More</button>
        </div>
      </div>
    </div>
```
```css
@media (max-width: 767px) {
    .card {
        width: 18rem;
        
    }
    .sedan-card {
        border-top-right-radius: 20px;
        border-bottom-right-radius: 0%;
        border-top-left-radius: 20px;
        border-bottom-left-radius: 0%;
    }

    .suvs-card {
        border-radius: 0%;
    }

    .luxury-card {
        border-top-right-radius: 0%;
        border-bottom-right-radius: 20px;
        border-top-left-radius: 0%;
        border-bottom-left-radius: 20px;
    }
}

```
## Author
- Frontend Mentor - [sonnen99](https://www.frontendmentor.io/profile/sonnen99)