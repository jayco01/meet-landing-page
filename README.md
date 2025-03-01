# Frontend Mentor - Meet Landing Page Solution

This is a solution to the Meet Landing Page challenge on Frontend Mentor.

## Table of Contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Live Demo](#live-demo)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Challenges Faced](#challenges-faced)
  - [Continued Development](#continued-development)
- [Author](#author)

---

## Overview

### Screenshot

![Meet Landing Page Screenshot](starter-code/assets/main-landing-page-capture1.png)

### Live Demo

- **Live Site URL:** [View Project](https://jayco01.github.io/meet-landing-page/)

---

## My Process

### Built With

- **Semantic HTML5**
- **CSS Grid**
- **Flexbox**
- **Background Linear Gradient** (for image overlay)
- **Mobile-first workflow**

### What I Learned

This project helped me strengthen my understanding of **CSS Grid and Flexbox**, as well as how to analyze a design in **Figma** and convert it into a working layout.

Some key takeaways:
- **Overlaying a background image with a color shader** using `linear-gradient()`
- **Structuring a responsive layout** with **CSS Grid & Flexbox**
- **Refining layout dimensions by inspecting a Figma design**

### Challenges Faced

One of the most difficult parts of this challenge was **overlaying different elements on top of each other**. A specific example is the **footer section**, where the `.number` element is partially overlaid on `.offer` while ensuring responsiveness.

Here’s a snippet of how I achieved the overlay:
```css
.numwrapper--2 {
  margin: 0;
  position: relative;
}

.numwrapper--2 .number {
  margin-bottom: -25px; /* Moves the element up */
  background-color: white;
}
```
Additionally, properly layering a **color overlay on a background image** was another challenge. I solved this using `linear-gradient()` before the background image:
```css
.offer {
  background: linear-gradient(rgba(76, 149, 169, 0.8), rgba(76, 149, 169, 0.8)),
              url('starter-code/assets/mobile/image-footer.jpg') center/cover no-repeat;
}
```

### Continued Development

Moving forward, I want to **improve my ability to navigate Figma efficiently**. Since Figma is an industry-standard tool for designers, it's essential for me as a developer to understand how to inspect and extract design details effectively.

---

## Author

- GitHub - [@jayco01](https://github.com/jayco01)

