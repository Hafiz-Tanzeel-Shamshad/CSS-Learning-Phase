# CSS Learning Phase – Part 6
# 🎨 CSS Layout & Animation Projects

This repository contains a collection of projects demonstrating modern **CSS techniques** including **Flexbox, Grid, animations, and responsive design**.

---
## Key Takeaways

- **Flexbox:** Ideal for 1D layouts and content distribution.  
- **Grid:** Perfect for complex 2D layouts.  
- **Animations:** Create engaging interfaces with CSS-only effects.  
- **Responsive Design:** Adapt layouts to different screen sizes.  
- **Z-index:** Control stacking order of positioned elements.
---
## Project Structure

### 1. Pet Adoption Website (Flexbox)
- **Files:** `pet-adoption.html`, `pet-adoption.css`  
- **Concepts:**
  - Flexbox layout for cards  
  - Responsive design with media queries  
  - Image styling and `border-radius`  
  - Semantic HTML structure  

### 2. CSS Animations
- **Files:** `animations.html`, `animations.css`  
- **Concepts:**
  - `@keyframes` animations  
  - Multiple animation properties  
  - Animation shorthand syntax  
  - Percentage-based keyframes  
  - Transform properties  

### 3. Media Queries
- **Files:** `media-queries.html`, `media-queries.css`  
- **Concepts:**
  - Viewport-based styling  
  - `min-width` and `max-width`  
  - Orientation detection  
  - Responsive design patterns  

### 4. Z-Index Positioning
- **Files:** `z-index.html`, `z-index.css`  
- **Concepts:**
  - Stacking context  
  - Relative positioning  
  - `z-index` property  
  - Element layering  

### 5. CSS Grid Basics
- **Files:** `grid-basics.html`, `grid-basics.css`  
- **Concepts:**
  - Grid container setup  
  - `fr` units  
  - Gap properties  
  - Item placement  
  - Self-alignment  

### 6. Complete Layout with Grid
- **Files:** `full-layout.html`, `full-layout.css`  
- **Concepts:**
  - 12-column grid system  
  - Responsive grid reflow  
  - Named template areas  
  - Viewport units  
  - Media queries for grid  

---
## Key CSS Concepts

### Flexbox Example
```css
#pets {
  display: flex;
  justify-content: space-evenly;
}

@media (max-width: 375px) {
  #pets {
    flex-wrap: wrap;
  }
}
```
### Animation Example
```css
.box {
  animation: widthAnimate 3s ease-in-out 1s infinite normal;
}

@keyframes widthAnimate {
  from { width: 10px; background-color: green; }
  to { width: 400px; background-color: yellowgreen; }
}
```
### Grid Example
```css
.container {
  display: grid;
  grid-template-rows: repeat(12, 1fr);
  grid-template-columns: repeat(12, 1fr);
  grid-gap: 10px;
}

.header {
  grid-column: 1 / 13;
}
```
### Media Query Example
```css
@media (min-width: 200px) and (max-width: 300px) {
  h1 {
    background-color: mediumvioletred;
  }
}
```

## Resources
- [CSS Tricks Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)  
- [MDN CSS Grid Layout](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout)  
- [CSS Animations Guide](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Animations/Using_CSS_animations)  
- [Responsive Design Basics](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design)

