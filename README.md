# Frontend Mentor - Product Preview Card Component Solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.




## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

![Design preview for the Product preview card component coding challenge](./design/desktop-preview.jpg)

### Features

- Responsive design that adapts to different screen sizes
- Interactive "Add to Cart" button with hover and focus states
- Semantic HTML structure for better accessibility
- Mobile-first approach with responsive images

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Responsive images with the `<picture>` element

### What I learned

This project helped me practice several important web development concepts:

- Using CSS custom properties for consistent design tokens
- Implementing responsive layouts with flexbox
- Creating responsive images with the `<picture>` element
- Building accessible components with semantic HTML
- Using proper CSS organization and structure

Example of responsive image implementation:

```html
<picture>
  <source media="(min-width: 640px)" srcset="./images/image-product-desktop.jpg">
  <img src="./images/image-product-mobile.jpg" alt="Gabrielle Essence Eau De Parfum bottle lying flat with green leaves around it">
</picture>
```

Using CSS custom properties for consistent design:

```css
:root {
  /* Primary Colors */
  --color-green-500: hsl(158, 36%, 37%);
  --color-green-700: hsl(158, 42%, 18%);
  --color-cream: hsl(30, 38%, 92%);

  /* Neutral Colors */
  --color-black: hsl(212, 21%, 14%);
  --color-grey: hsl(228, 12%, 48%);
  --color-white: hsl(0, 0%, 100%);
}
```

### Useful resources

- [MDN Web Docs](https://developer.mozilla.org/en-US/) - Comprehensive web development documentation
- [CSS-Tricks Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Helpful guide for understanding flexbox
- [A Complete Guide to CSS Media Queries](https://css-tricks.com/a-complete-guide-to-css-media-queries/) - Great resource for responsive design

## Author

- Frontend Mentor - [@Ayokanmi-Adejola](https://www.frontendmentor.io/profile/Ayokanmi-Adejola)
