# mtm6201-final

# Pawsitive Futures – Final Project

## About the Project
This project is a responsive website for a fictional animal shelter called *Pawsitive Futures*. The goal of the site is to promote pet adoption, share success stories, and encourage users to get involved. The design was based on mockups and wireframes created earlier in the User Experience Design course.

The website includes multiple pages:
- Home
- About
- Adopt

Each page was designed to be visually consistent, accessible, and responsive across different screen sizes.

---

## My Process
I started by reviewing my Figma designs and breaking them down into sections like header, hero, cards, and footer. From there, I built the HTML structure first using semantic elements such as `<header>`, `<main>`, `<section>`, and `<footer>` to keep everything organized and accessible.

After that, I styled everything using CSS. I focused on creating reusable classes like cards, buttons, and layout containers so my code stayed consistent across pages. I also used media queries to adjust layouts for tablet and desktop views.

For images, I used the `<picture>` element with different sizes so that smaller images load on mobile devices. This helps with performance and responsiveness.

---

## Challenges and How I Solved Them

### 1. Layout Issues (especially side-by-side sections)
One of my biggest challenges was getting sections (like the About cards) to sit side-by-side properly on larger screens without breaking the layout. At first, things looked squished or misaligned.

I experimented with both Flexbox and Grid, and eventually used CSS Grid for cleaner alignment. I also adjusted widths and spacing so the cards didn’t feel cramped.

---

### 2. Responsive Design
Making sure everything looked good on mobile, tablet, and desktop was harder than I expected. Some elements were too big or stacked weirdly.
 
I used media queries (`@media`) to change layouts depending on screen size. For example, cards stack on mobile but display in rows on larger screens.

---

### 3. Button and Spacing Issues
Some buttons (like the call-to-action) were too big or too close to other elements.
 
I adjusted padding, margins, and used `width: fit-content` along with `margin: auto` to center and size them properly.

---

### 4. Accessibility
Understanding how to properly use ARIA attributes and roles was a bit confusing at first.

I researched what each attribute does and applied them where needed, like:
- `aria-label` for navigation
- `aria-expanded` for the menu toggle
- `role="main"` and `role="banner"` for structure

---

## What I Learned
From this project, I learned:
- How to build a full multi-page website from scratch
- How important planning (wireframes and mockups) is before coding
- How to use semantic HTML for better accessibility
- How to create responsive layouts using Flexbox and Grid
- How to troubleshoot layout and spacing issues more efficiently
- How to think more like a real developer when organizing code

I also improved my confidence in writing HTML and CSS without relying too much on tutorials.

---

## Assets and Resources

### Fonts
- Google Fonts:
  - Elsie
  - Capriola
Custom Font: 
  - Beauty Rachela
  - Designed by Yudi Pratama Chandra (Rantautype Studio)
  - Source: https://www.dafont.com/beauty-rachela.font

### Images
- All images are from adobe stock 
- Images were optimized using deriv 

### Icon Attributes

<a href="https://www.flaticon.com/free-icons/contact" title="contact icons">Contact icons created by Cuputo - Flaticon</a>
<a href="https://www.flaticon.com/free-icons/paws" title="paws icons">Paws icons created by Icons_Field - Flaticon</a>
<a href="https://www.flaticon.com/free-icons/portfolio" title="portfolio icons">Portfolio icons created by Freepik - Flaticon</a>
<a href="https://www.flaticon.com/free-icons/care" title="care icons">Care icons created by Bharat Icons - Flaticon</a>
<a href="https://www.flaticon.com/free-icons/house" title="house icons">House icons created by Freepik - Flaticon</a>


### Figma File link

## Figma Mockups

Below are my final mockups created in Figma. These designs were used as the foundation for building the website layout, structure, and visual style.

### Home Page
<img src="images/homepage-tablet-mockup.png">

<img src="images/hompage-mobile-mockup.png">

<img src="images/homepage-desktop-mockup.png">


---

### About Page
<img src="images/aboutpage-desktop-mockup.png">

<img src="images/aboutpage-mobile-mockup.png">

<img src="images/aboutpage-tablet-mockup.png">

---

### Adopt Page
<img src="images/adoptpage-desktop-mockup.png">

<img src="images/adoptpage-mobile-mockup.png">

<img src="images/adoptpage-tablet-mockup.png">


## Final Notes
This project helped me understand how all the pieces of web development come together, from design to development to deployment. If I had more time, I would improve animations and add more interactivity, but overall I’m really happy with how the site turned out.