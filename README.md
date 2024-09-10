# Make It Real - the my-team-page

This is a solution to the my-team-page project of the Make It Real course.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
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

- View my computer's website on different screens, whether desktop or cell phone

### Screenshot

  #### Desktop
  ![image](https://github.com/user-attachments/assets/5c9327b5-e5a2-43e1-9bed-80f1065590d8)

  #### Mobile
  ![image](https://github.com/user-attachments/assets/68a8b7eb-6296-4cd5-be37-666130c15f1d)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

While working through this project, I solidified my understanding of responsive design principles, particularly in how to handle different screen sizes using CSS Grid and media queries. I also improved my skills in implementing the BEM methodology for organizing CSS classes, which helps to maintain scalability and readability in stylesheets.

Some key takeaways include:

```html
<h1 class="team__title">The creative crew</h1>
```

```css
.team__members {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}
```

### Continued development

For future projects, I want to keep focusing on enhancing my use of CSS Grid to create more complex layouts, and I aim to continue refining my approach to responsive design. Additionally, I’m looking to improve my use of asynchronous JavaScript, especially for handling API requests efficiently and optimizing page performance.

### Useful resources

- [CSS Grid Layout](https://developer.mozilla.org/es/docs/Web/CSS/CSS_grid_layout) - This resource helped me understand how to make my layout more responsive and flexible. I'll definitely use it again in future projects.
## Author

- Github - [GabrielMaQui](https://github.com/GabrielMaQui)

## Acknowledgments

I would like to thank the instructors at Make It Real for their guidance and support throughout this project.
