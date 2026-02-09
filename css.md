# 📘 Complete CSS & CSS3 Reference Documentation

This repository contains a **complete and well-structured reference of CSS and CSS3**.
Useful for **beginners, students, interviews, exams, frontend developers, and quick revision**.

---

## 📌 1. CSS Basics

* CSS Syntax
* Selectors
* Properties
* Values
* CSS Comments (`/* */`)
* Cascade
* Inheritance
* Specificity

---

## 📌 2. Ways to Apply CSS

* Inline CSS
* Internal CSS
* External CSS
* `@import` Rule

---

## 📌 3. CSS Selectors

### Basic Selectors

* Universal Selector (`*`)
* Element Selector
* Class Selector (`.class`)
* ID Selector (`#id`)

### Attribute Selectors

* `[attr]`
* `[attr=value]`
* `[attr^=value]`
* `[attr$=value]`
* `[attr*=value]`

### Combinators

* Descendant (`div p`)
* Child (`div > p`)
* Adjacent Sibling (`h1 + p`)
* General Sibling (`h1 ~ p`)

---

## 📌 4. CSS Pseudo Classes

* `:hover`
* `:active`
* `:focus`
* `:visited`
* `:link`
* `:checked`
* `:disabled`
* `:enabled`
* `:first-child`
* `:last-child`
* `:nth-child()`
* `:not()`

---

## 📌 5. CSS Pseudo Elements

* `::before`
* `::after`
* `::first-letter`
* `::first-line`
* `::selection`

---

## 📌 6. CSS Colors

* Named Colors
* HEX
* RGB
* RGBA
* HSL
* HSLA
* `currentColor`

---

## 📌 7. CSS Background Properties

* `background-color`
* `background-image`
* `background-repeat`
* `background-position`
* `background-size`
* `background-attachment`
* `background-origin`
* `background-clip`
* `background` (shorthand)

---

## 📌 8. CSS Text Properties

* `color`
* `text-align`
* `text-decoration`
* `text-transform`
* `text-indent`
* `letter-spacing`
* `word-spacing`
* `line-height`
* `white-space`
* `word-break`
* `overflow-wrap`

---

## 📌 9. CSS Font Properties

* `font-family`
* `font-size`
* `font-weight`
* `font-style`
* `font-variant`
* `font-stretch`
* `font` (shorthand)

---

## 📌 10. CSS Box Model

* `width`
* `height`
* `padding`
* `border`
* `margin`
* `box-sizing`

---

## 📌 11. CSS Border & Outline

* `border-width`
* `border-style`
* `border-color`
* `border-radius`
* `outline`
* `outline-offset`

---

## 📌 12. CSS Display & Visibility

* `display: block`
* `display: inline`
* `display: inline-block`
* `display: none`
* `visibility: hidden`

---

## 📌 13. CSS Positioning

* `position: static`
* `position: relative`
* `position: absolute`
* `position: fixed`
* `position: sticky`
* `top`
* `right`
* `bottom`
* `left`
* `z-index`

---

## 📌 14. CSS Float & Clear

* `float: left`
* `float: right`
* `clear: both`

---

## 📌 15. CSS Overflow

* `overflow`
* `overflow-x`
* `overflow-y`

---

## 📌 16. CSS Flexbox (CSS3)

* `display: flex`
* `flex-direction`
* `flex-wrap`
* `justify-content`
* `align-items`
* `align-content`
* `gap`
* `flex-grow`
* `flex-shrink`
* `flex-basis`
* `order`

---

## 📌 17. CSS Grid (CSS3)

* `display: grid`
* `grid-template-columns`
* `grid-template-rows`
* `grid-gap`
* `grid-column`
* `grid-row`
* `justify-items`
* `align-items`
* `place-items`

---

## 📌 18. CSS Units

### Absolute Units

* `px`
* `cm`
* `mm`
* `in`

### Relative Units

* `%`
* `em`
* `rem`
* `vw`
* `vh`
* `vmin`
* `vmax`

---

## 📌 19. CSS Transforms (CSS3)

* `transform: translate()`
* `transform: scale()`
* `transform: rotate()`
* `transform: skew()`

---

## 📌 20. CSS Transitions (CSS3)

* `transition-property`
* `transition-duration`
* `transition-timing-function`
* `transition-delay`
* `transition` (shorthand)

---

## 📌 21. CSS Animations (CSS3)

* `@keyframes`
* `animation-name`
* `animation-duration`
* `animation-delay`
* `animation-iteration-count`
* `animation-direction`
* `animation-fill-mode`
* `animation-play-state`

---

## 📌 22. CSS Media Queries (Responsive Design)

Used to make layouts responsive for different screen sizes.

* `@media screen`
* `@media print`
* `min-width`
* `max-width`
* `orientation`

### Common Breakpoints

* Mobile: `max-width: 576px`
* Tablet: `max-width: 768px`
* Laptop: `max-width: 992px`
* Desktop: `min-width: 1200px`

### Example: Responsive Layout

```css
/* Mobile First */
body {
  font-size: 14px;
}

@media (min-width: 768px) {
  body {
    font-size: 16px;
  }
}

@media (min-width: 1024px) {
  body {
    font-size: 18px;
  }
}
```

### Example: Responsive Flexbox

```css
.container {
  display: flex;
  flex-direction: column;
}

@media (min-width: 768px) {
  .container {
    flex-direction: row;
  }
}
```

---

## 📌 23. CSS Variables (Custom Properties)

* `--variable-name`
* `var()`

---

## 📌 24. CSS Shadows (CSS3)

* `box-shadow`
* `text-shadow`

---

## 📌 25. CSS Gradients (CSS3)

* `linear-gradient()`
* `radial-gradient()`
* `conic-gradient()`

---

## 📌 26. CSS Filters (CSS3)

* `blur()`
* `brightness()`
* `contrast()`
* `grayscale()`
* `sepia()`

---

## 📌 27. CSS Opacity & Visibility

* `opacity`
* `visibility`

---

## 📌 28. CSS Cursor & User Interaction

* `cursor`
* `pointer-events`
* `user-select`

---

## 📌 29. CSS List & Table Styling

* `list-style`
* `list-style-type`
* `list-style-position`
* `border-collapse`
* `table-layout`

---

## 📌 30. CSS Best Practices

* Use external CSS
* Prefer class selectors
* Mobile-first design
* Avoid excessive `!important`
* Keep CSS modular

---

## ✅ Notes

* Covers **complete CSS + CSS3**
* Deprecated properties excluded
* Ideal for **README.md, exams, interviews, revision**

---

⭐ Happy Styling 🎨

---

## 📌 31. Complete Responsive Layout (Header – Sidebar – Content)

### HTML Structure (Reference)

```html
<header class="header">Header</header>
<div class="layout">
  <aside class="sidebar">Sidebar</aside>
  <main class="content">Main Content</main>
</div>
<footer class="footer">Footer</footer>
```

### CSS (Mobile First)

```css
body {
  margin: 0;
  font-family: Arial, sans-serif;
}

.header, .footer {
  background: #222;
  color: #fff;
  padding: 15px;
  text-align: center;
}

.layout {
  display: flex;
  flex-direction: column;
}

.sidebar {
  background: #f4f4f4;
  padding: 15px;
}

.content {
  padding: 15px;
}

@media (min-width: 768px) {
  .layout {
    flex-direction: row;
  }

  .sidebar {
    width: 250px;
  }
}
```

---

## 📌 32. Grid + Flex Combined Responsive Example

### CSS Grid for Page Layout

```css
.page {
  display: grid;
  grid-template-columns: 1fr;
}

@media (min-width: 768px) {
  .page {
    grid-template-columns: 200px 1fr;
  }
}
```

### Flexbox for Cards

```css
.cards {
  display: flex;
  flex-wrap: wrap;
  gap: 15px;
}

.card {
  flex: 1 1 100%;
  background: #eee;
  padding: 20px;
}

@media (min-width: 768px) {
  .card {
    flex: 1 1 calc(33.333% - 15px);
  }
}
```

---

## 📌 33. Responsive Images & Media

* `max-width: 100%`
* `height: auto`
* `object-fit`

```css
img {
  max-width: 100%;
  height: auto;
}

video {
  width: 100%;
  height: auto;
}
```

---

## 📌 34. Responsive Typography

```css
html {
  font-size: 14px;
}

@media (min-width: 768px) {
  html {
    font-size: 16px;
  }
}

@media (min-width: 1200px) {
  html {
    font-size: 18px;
  }
}
```

---

## 📌 35. Responsive Utility Classes

```css
.hide-mobile {
  display: none;
}

@media (min-width: 768px) {
  .hide-mobile {
    display: block;
  }
}
```

---

## 📌 36. Responsive CSS Cheatsheet

### Breakpoints

* 320px – Small mobile
* 576px – Mobile
* 768px – Tablet
* 992px – Laptop
* 1200px – Desktop

### Common Rules

```css
/* Mobile First */
.container {
  padding: 10px;
}

@media (min-width: 768px) {
  .container {
    padding: 20px;
  }
}
```

---

## 📌 37. Responsive Best Practices

* Always use mobile-first CSS
* Avoid fixed widths
* Use Flexbox and Grid
* Use relative units (`rem`, `%`, `vw`)
* Test on real devices

---

## 📌 38. CSS + CSS3 + Responsive Summary

* Core CSS properties covered
* CSS3 modules included
* Media queries fully covered
* Flexbox + Grid responsive layouts
* Production-ready examples

---

## ✅ Final Notes

* This README covers **FULL CSS + CSS3 + RESPONSIVE DESIGN**
* Nothing important is skipped
* Suitable for **GitHub repo, exams, interviews, and real projects**

---

⭐ Happy Responsive Coding 🚀
