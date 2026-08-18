# Grid

The **Grid** utilities help you align and position items inside a CSS Grid container.

Uxiora provides simple and consistent utility classes for controlling grid alignment without writing custom CSS.

---

# Why Use Grid Utilities?

Grid utilities help you:

- Build two-dimensional layouts
- Align grid items easily
- Create responsive interfaces
- Reduce custom CSS
- Keep layouts clean and maintainable

---

# Prerequisite

Before using any Grid utility, make sure the element is a Grid container.

```html
<div class="dis-g">
    ...
</div>
```

Without the `dis-g` class, Grid alignment utilities will not work.

---

# Justify Self

Controls the horizontal alignment of an individual grid item.

| Class | CSS |
|--------|-------------------------|
| js-auto | justify-self: auto; |
| js-start | justify-self: start; |
| js-end | justify-self: end; |
| js-center | justify-self: center; |
| js-stretch | justify-self: stretch; |

Example

```html
<div class="dis-g">
    <div class="js-center">
        Grid Item
    </div>
</div>
```

---

# Justify Items

Controls the horizontal alignment of all grid items.

| Class | CSS |
|--------|--------------------------|
| ji-start | justify-items: start; |
| ji-end | justify-items: end; |
| ji-center | justify-items: center; |
| ji-stretch | justify-items: stretch; |

Example

```html
<div class="dis-g ji-center">
    ...
</div>
```

---

# Place Items

Shorthand for `align-items` and `justify-items`.

| Class | CSS |
|--------|------------------------|
| pi-start | place-items: start; |
| pi-end | place-items: end; |
| pi-center | place-items: center; |
| pi-stretch | place-items: stretch; |

Example

```html
<div class="dis-g pi-center">
    ...
</div>
```

---

# Place Content

Controls the alignment of the entire grid.

| Class | CSS |
|--------|--------------------------------|
| pc-start | place-content: start; |
| pc-end | place-content: end; |
| pc-center | place-content: center; |
| pc-between | place-content: space-between; |
| pc-around | place-content: space-around; |
| pc-evenly | place-content: space-evenly; |
| pc-stretch | place-content: stretch; |

Example

```html
<div class="dis-g pc-center">
    ...
</div>
```

---

# Place Self

Controls the alignment of a single grid item.

| Class | CSS |
|--------|------------------------|
| ps-auto | place-self: auto; |
| ps-start | place-self: start; |
| ps-end | place-self: end; |
| ps-center | place-self: center; |
| ps-stretch | place-self: stretch; |

Example

```html
<div class="dis-g">
    <div class="ps-center">
        Grid Item
    </div>
</div>
```

---

# Combining Grid Utilities

Grid utilities are designed to work together.

Example

```html
<div class="dis-g pi-center pc-center pd-6 shadow-md br-md">

    <div class="ps-center">
        Welcome to Uxiora
    </div>

</div>
```

---

# Best Practices

- Always use `dis-g` before applying Grid utilities.
- Use `ji-*` to align all grid items.
- Use `js-*` to align individual grid items.
- Use `pi-*` for simple centering.
- Use `pc-*` when aligning the entire grid content.
- Use `ps-*` to override the alignment of a single item.

---

# Common Examples

### Center a Grid Item

```html
<div class="dis-g pi-center">
    <div>Centered Item</div>
</div>
```

---

### Align a Single Item

```html
<div class="dis-g">
    <div class="ps-end">
        Last Item
    </div>
</div>
```

---

### Center the Entire Grid

```html
<div class="dis-g pc-center">
    ...
</div>
```

---

# Related Utilities

- Display
- Flex
- Position
- Spacing
- Border