<h1 style="text-align: center;">CSS Learning Phase – Part 3</h1>

## Box Model & Layout Fundamentals 🎨


This project demonstrates core CSS concepts including the box model, display properties, units, and layout techniques through practical examples.

## Key Takeaways

- **Box Model:** Every element is a rectangular box with content, padding, border, and margin.  
- **Display Types:** Understand inline vs block vs inline-block behaviors.  
- **Relative Units:** Use `em`, `rem`, `%` for flexible, scalable designs.  
- **Margin Collapse:** Vertical margins between elements collapse.  
- **Border Tricks:** Combine different border styles for creative effects.

---

### 1. Basic Box Model
- **Files**: `box-model.html`, `box-model.css`
- **Concepts**:
  - Element dimensions (width/height)
  - Borders (style, width, color)
  - Margins and padding
  - `display: inline-block`
  - Hiding elements (`display: none`)

### 2. Relative Sizing
- **Files**: `relative-sizing.html`, `relative-sizing.css`
- **Concepts**:
  - Percentage-based widths
  - Nested div relationships
  - Margin percentages relative to parent

### 3. EM vs REM Units
- **Files**: `units.html`, `units.css`
- **Concepts**:
  - `em` units (relative to parent font-size)
  - `rem` units (relative to root font-size)
  - Padding with relative units
  - Button styling with em units

### 4. Practical Layouts
- **Files**: `layouts.html`, `layouts.css`
- **Concepts**:
  - Shorthand margin/padding notation
  - Circular elements (`border-radius: 50%`)
  - Inline list items
  - Box model visualization

### 5. Traffic Light Project
- **Files**: `traffic-light.html`, `traffic-light.css`
- **Concepts**:
  - Vertical stacking of elements
  - Circular shapes
  - Color semantics
  - Fixed dimension containers

### 6. Advanced Borders
- **Files**: `advanced-borders.html`, `advanced-borders.css`
- **Concepts**:
  - Mixed border styles
  - Individual border properties
  - Rounded corners (uniform and specific)
  - Complex margin/padding

### 7. Inline vs Block
- **Files**: `display.html`, `display.css`
- **Concepts**:
  - Natural display behaviors
  - Forcing block/inline display
  - Limitations of inline elements
  - Box model differences

## Key CSS Concepts Demonstrated

### Box Model Components
```css
div {
  width: 200px;         /* Content width */
  height: 150px;        /* Content height */
  padding: 20px;        /* Inner spacing */
  border: 2px solid #000; /* Visible border */
  margin: 10px;         /* Outer spacing */
  box-sizing: border-box; /* Alternative box model */
}
```
## Display Properties

```css
.inline {
  display: inline;       /* No width/height, flows with text */
}

.block {
  display: block;        /* Takes full width by default */
}

.inline-block {
  display: inline-block; /* Flows like inline but respects dimensions */
}

.hidden {
  display: none;         /* Completely removed from layout */
}
```
## Relative Units

```css
.ems {
  font-size: 1.5em;    /* 1.5 × parent font size */
  padding: 1em;        /* Relative to current font size */
}

.rems {
  font-size: 1.5rem;   /* 1.5 × root (html) font size */
}

.percent {
  width: 50%;          /* Percentage of parent width */
  margin-left: 10%;    /* Percentage of parent width */
}
```
## Border Techniques

```css
.mixed-borders {
  border: 2px solid black;
  border-top: 3px dashed blue;
  border-radius: 20px;
  border-bottom-right-radius: 50px;
}
```
---
## Resources
- [MDN Box Model Guide](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)  
- [CSS Display Property](https://developer.mozilla.org/en-US/docs/Web/CSS/display)  
- [CSS Units Guide](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Values_and_units)  
- [Border Properties](https://developer.mozilla.org/en-US/docs/Web/CSS/border)

---
