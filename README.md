# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 
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

- See hover and focus states for all interactive elements on the page

  ### Screenshot
![Frontend Mentor _ Blog preview card - Google Chrome 10-03-2024 16_10_23](https://github.com/babybhavani/blogPreviewCard/assets/152834101/5c86fd4d-548c-4776-ad9d-f9c02b469c00)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
  
### What I learned

- I learned about what are the best practices to set the height and width of an element.
- Improved my designings.
- Developing Flexbox layout.
- Styling Flexbox layout.
- Aligning Items of a card or a container element.

### Iam Proud of this code
```html
 <main class="container">
    <section class="card-container">
        <section class="top-section">
            <img src="assets\images\illustration-article.svg" class="image-top">
        </section>
        <section class="bottom-section">
          <button class="btn">Learning</button>
          <p class="about">Published 21 Dec 2923</p>
          <h1 class="card-heading">HTML & CSS foundations</h1>
          <p class="card-description">These languages are backbone of every website, defining structure, content and presentation. </p>
          <ul >
            <li><img class="profile" src="assets\images\image-avatar.webp"></li>
            <li class="name">Greg Hopper</li>
          </ul>
        </section>
      </section>
  </main>
```
```css
.card-heading:hover
{
  color: hsl(47, 83%, 63%);
  cursor: pointer;
}
```
### Continued development

I want to continue development in the area of description of card. i.e. developing user interactions utilising JavaScript. As I'm a learner it is mandatory to be consistent.

### Useful resources
- [Example resource 1](https://www.w3schools.com) - This helped me understanding the flexbox properties. I really liked this pattern and will use it going forward.

## Author
- Frontend Mentor - [@babybhavani](https://www.frontendmentor.io/profile/babybhavani)
  
## Acknowledgments

Thnks to Frontend Mentor to get me a chance to develop my skills in HTML and CSS.
