# 🎨 CSS — Part 2 

A collection of HTML/CSS examples demonstrating fundamental to advanced CSS concepts including inheritance, selectors, pseudo-classes, and responsive design.
---
## Project Structure

### 1. Inheritance Demo
- **Files**: `inheritance_demo.html`, `inheritance_style.css`
- **Key Concepts**:
  - CSS inheritance with `inherit` keyword
  - Form element styling
  - Background color inheritance
  - Hover effects
  - Input field styling

### 2. Quora-like Page
- **Files**: `index.html`, `style.css`, `style2.css`
- **Key Concepts**:
  - Multiple CSS files and precedence
  - Selector specificity (`!important` flag)
  - Complex selectors (descendant, child, adjacent sibling)
  - Attribute selectors
  - Pseudo-classes (`:hover`, `:active`, `:checked`)
  - Pseudo-elements (`::first-letter`, `::first-line`)
  - Structural pseudo-classes (`:nth-of-type`)
  - Text selection styling

### 3. Facebook-like Practice
- **Files**: `PracticeQs.html`, `practice_style.css`
- **Key Concepts**:
  - Universal selector (`*`)
  - ID vs class selectors
  - Button styling
  - Input field styling

## Key CSS Concepts Demonstrated

### Selector Types
```css
/* Element selector */
h1 { color: red; }

/* Class selector */
.userbtn { background: aqua; }

/* ID selector */
#searchbtn { background: black; }

/* Attribute selector */
input[type="text"] { color: green; }

/* Descendant selector */
nav a { color: lightsalmon; }

/* Child selector */
div > input { background: darksalmon; }

/* Adjacent sibling selector */
.upvote + button { background: cadetblue; }
```
## Pseudo-classes & Elements

```css
/* Hover effect */
button:hover { 
  background: black; 
}

/* Active state */
button:active { 
  background: palevioletred; 
}
```
## Specificity & Inheritance

```css
/* Inheritance example */
input, button { 
  background-color: inherit; 
}

/* !important override */
h3 { 
  background-color: rgb(158, 108, 158) !important; 
}


/* Specificity example */
div#myid { 
  background-color: rgb(0, 37, 245); 
}


/* Checked state */
input[type="radio"]:checked + label { 
  color: red; 
}

/* First letter */
h1::first-letter { 
  color: green; 
}

/* First line */
p::first-line { 
  color: purple; 
}
```
## Structural Styling

```css
/* Alternate row styling */
.posts:nth-of-type(2n) { 
  background-color: aqua; 
}
```
## Key Takeaways

- **Inheritance:** Child elements inherit properties from parents when set to `inherit`.  
- **Specificity:** ID selectors > class selectors > element selectors.  
- **Pseudo-classes:** Style elements in special states (`:hover`, `:active`).  
- **Advanced Selectors:** Precisely target elements with complex selectors.  
- **Maintainability:** Use external stylesheets for better code organization.
## Resources
- [MDN CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS)  
- [CSS Selectors Guide](https://www.w3schools.com/css/css_selectors.asp)  
- [Specificity Calculator](https://specificity.keegan.st/)  
- [Pseudo-classes Reference](https://www.w3schools.com/cssref/css_selectors.asp#pseudo-classes)
