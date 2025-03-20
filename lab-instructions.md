# HTML & CSS Lab: Build a Travel Blog

## Overview
In this lab, you'll create a simple travel blog called "Wanderlust" using HTML and CSS. This project will help you practice fundamental web development concepts including semantic HTML, CSS layouts, responsive design, and styling techniques.

## Learning Objectives
- Apply semantic HTML elements to structure a web page
- Use CSS Flexbox for page layout 
- Implement a responsive design that works on different screen sizes
- Practice CSS styling techniques for text, borders, and backgrounds
- Add simple interactivity with CSS hover effects

## Requirements

### Structure (HTML)
1. Create an `index.html` file with the following sections:
   - Header with site title and navigation
   - Hero section with a large image and headline
   - Feature section with 3 travel destinations (each with image, title, and description)
   - Photo gallery section using CSS Grid
   - About section with text about the blog
   - Footer with copyright information

2. Use appropriate semantic HTML elements:
   - `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`
   - Use `<h1>`, `<h2>`, etc. for headings, following proper hierarchy
   - Use `<p>` for paragraphs and `<a>` for links
   - Include at least one unordered list `<ul>` in the navigation

### Styling (CSS)
1. Create a `styles.css` file and link it to your HTML
2. Implement the following styling requirements:
   - Use a color scheme of your choice (suggested: blues/greens for a travel theme)
   - Set appropriate font sizes, weights, and families
   - Add padding, margins, and borders where needed for visual spacing
   - Style the navigation links (horizontal alignment, no bullet points)
   - Style the feature section using Flexbox to display destinations side by side on larger screens
   - Create a photo gallery using CSS Grid for a dynamic layout
   - Make the layout responsive (stack items vertically on small screens)
   - Add hover effects to links, destination cards, and gallery images

## Design Hints
- **Navigation:** Use Flexbox for horizontal alignment of nav items (`display: flex`)
- **Feature Section:** Flexbox works well here too! Use `flex-wrap: wrap` so items stack on smaller screens
- **Hero Section:** Consider using `background-image` with `background-size: cover` for a full-width image
- **Photo Gallery:** Use CSS Grid (`display: grid`) with `grid-template-columns` and `grid-gap` for a dynamic layout
- **Grid Responsiveness:** Adjust the number of columns in your grid using `repeat()` and `minmax()` functions
- **Responsive Design:** Use media queries (`@media screen and (max-width: 768px) { ... }`) to adjust layout for mobile
- **Spacing:** Use margin and padding to create comfortable whitespace between elements
- **Typography:** Choose readable fonts, and consider using Google Fonts for more options

## Step-by-Step Guide

### 1. HTML Structure
1. Start by creating the basic HTML structure with `<!DOCTYPE html>`, `<html>`, `<head>`, and `<body>` tags
2. Add metadata in the head (title, charset, viewport)
3. Link your CSS file with `<link rel="stylesheet" href="styles.css">`
4. Create the header with site title and navigation menu
5. Build the hero section with a headline
6. Create the feature section with 3 destination articles
7. Add the about section with information about the blog
8. Finish with a simple footer

### 2. CSS Styling
1. Start with a CSS reset to normalize browser styles
2. Set base styles for typography (font-family, sizes, colors)
3. Style the header and navigation
4. Create the hero section styling
5. Use Flexbox to layout the feature section
6. Style individual destination cards
7. Add style to the about section
8. Format the footer
9. Add responsive styles with media queries

## Bonus Challenges
If you finish early, try these enhancements:
- Add a simple contact form in the footer
- Implement a sticky header that stays at the top when scrolling
- Add CSS transitions to your hover effects for smoother animations
- Enhance your grid gallery with different sized images using `grid-row` and `grid-column` properties
- Create a masonry-style layout for your gallery

## Resources
- [MDN Web Docs: HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [MDN Web Docs: CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [Google Fonts](https://fonts.google.com/)
- Free images: [Unsplash](https://unsplash.com/) or [Pexels](https://www.pexels.com/)

## Submission
When complete, submit your HTML and CSS files.

**Grading criteria:**
- Correct use of semantic HTML elements
- Proper implementation of CSS styling techniques
- Responsive design that works on different screen sizes
- Visual appeal and attention to detail
- Code organization and cleanliness
