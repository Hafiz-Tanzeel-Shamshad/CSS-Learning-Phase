# CSS Learning Phase – Part 5
# 🎨 CSS Flexbox Layout Projects 

This project demonstrates various implementations of **CSS Flexbox** for creating modern, responsive layouts. Each example showcases different Flexbox properties and techniques.

---
## Key Takeaways

- **Flex Direction:** Controls main axis orientation.  
- **Justify Content:** Distributes space along main axis.  
- **Align Items:** Controls cross-axis alignment.  
- **Flex Wrap:** Allows items to wrap to new lines.  
- **Flex Shorthand:** `flex: grow shrink basis`.  
- **Responsive:** Flexbox layouts adapt to container size.
---
### 1. Basic Flexbox Layout
- **Files:** `basic-flex.html`, `basic-flex.css`  
- **Concepts:**
  - Flex container and items  
  - `justify-content: space-between`  
  - Centering with `margin: auto`  
  - Nested flex containers  
  - Box model styling  

### 2. Flexbox Grid Assignment
- **Files:** `flex-grid.html`, `flex-grid.css`  
- **Concepts:**
  - `flex-wrap: wrap`  
  - `justify-content: space-evenly`  
  - `align-items: center`  
  - Square grid layout  
  - Centering content with `line-height`  

### 3. Complete Flexbox Project
- **Files:** `complete-flex.html`, `complete-flex.css`  
- **Concepts:**
  - Grid layout with flexbox  
  - Navigation bar styling  
  - `border-radius` for rounded corners  
  - Multiple flex containers  
  - Responsive width units  

### 4. Flexbox Playground
- **Files:** `flex-playground.html`, `flex-playground.css`  
- **Concepts:**
  - All `flex-direction` options  
  - All `justify-content` options  
  - `align-content` properties  
  - Individual item control (`align-self`)  
  - Flex `grow`/`shrink`/`basis`  

---

## Key Flexbox Concepts Demonstrated
### Container Properties
```css
.container {
  display: flex;           /* Creates flex context */
  flex-direction: row;     /* row | row-reverse | column | column-reverse */
  justify-content: center; /* Controls main axis alignment */
  align-items: center;     /* Controls cross axis alignment */
  flex-wrap: wrap;         /* nowrap | wrap | wrap-reverse */
  align-content: space-between; /* For multi-line flex containers */
}
```
### Item Properties
```css
.item {
  flex-grow: 1;        /* Ability to grow if extra space */
  flex-shrink: 1;      /* Ability to shrink if needed */
  flex-basis: 100px;   /* Default size before remaining space */
  flex: 1 1 100px;     /* Shorthand for above 3 properties */
  align-self: flex-start; /* Override container's align-items */
  order: 1;            /* Change visual order without changing HTML */
}
```
### Practical Examples
```css
/* Navigation bar */
#navbar {
  display: flex;
  justify-content: flex-start;
  align-items: center;
}

/* Centered grid */
#container {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-evenly;
  align-items: center;
}

/* Individual item control */
#special-item {
  align-self: flex-end;
  flex-grow: 2;
}
```
## Resources
- [CSS Tricks Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)  
- [MDN Flexbox Documentation](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox)  
- [Flexbox Froggy Game](https://flexboxfroggy.com/)  
- [Flexbox Visual Cheatsheet](https://flexbox.malven.co/)

