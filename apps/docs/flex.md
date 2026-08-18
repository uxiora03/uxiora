# Flex

The **Flex** utilities help you build flexible and responsive layouts using the CSS Flexbox module.

Uxiora provides simple and consistent utility classes for controlling flex direction, wrapping, alignment, and spacing without writing custom CSS.

---

# Why Use Flex Utilities?

Flex utilities help you:

- Build responsive layouts
- Align content easily
- Create horizontal and vertical layouts
- Reduce custom CSS
- Keep layouts clean and maintainable

---

# Prerequisite

Before using any Flex utility, make sure the element is a Flex container.

```html
<div class="dis-f">
    ...
</div>
```

Without the `dis-f` class, Flex utilities such as `jc-center` or `ai-center` will not work.

---

# Flex Direction

Control the direction of flex items.

| Class | CSS |
|--------|---------------------------|
| f-row | flex-direction: row; |
| f-row-r | flex-direction: row-reverse; |
| f-col | flex-direction: column; |
| f-col-r | flex-direction: column-reverse; |

Example

```html
<div class="dis-f f-row">
    ...
</div>
```

---

# Flex Wrap

Control whether flex items wrap onto multiple lines.

| Class | CSS |
|--------|----------------------|
| f-wrap | flex-wrap: wrap; |
| f-nowrap | flex-wrap: nowrap; |
| f-wrap-r | flex-wrap: wrap-reverse; |

Example

```html
<div class="dis-f f-wrap">
    ...
</div>
```

---

# Justify Content

Align items along the main axis.

| Class | CSS |
|--------|--------------------------------|
| jc-start | justify-content: flex-start; |
| jc-end | justify-content: flex-end; |
| jc-center | justify-content: center; |
| jc-between | justify-content: space-between; |
| jc-around | justify-content: space-around; |
| jc-evenly | justify-content: space-evenly; |

Example

```html
<div class="dis-f jc-center">
    ...
</div>
```

---

# Align Items

Align items along the cross axis.

| Class | CSS |
|--------|----------------------------|
| ai-start | align-items: flex-start; |
| ai-end | align-items: flex-end; |
| ai-center | align-items: center; |
| ai-baseline | align-items: baseline; |
| ai-stretch | align-items: stretch; |

Example

```html
<div class="dis-f ai-center">
    ...
</div>
```

---

# Align Content

Align multiple rows of wrapped flex items.

| Class | CSS |
|--------|--------------------------------|
| ac-start | align-content: flex-start; |
| ac-end | align-content: flex-end; |
| ac-center | align-content: center; |
| ac-between | align-content: space-between; |
| ac-around | align-content: space-around; |
| ac-evenly | align-content: space-evenly; |
| ac-stretch | align-content: stretch; |

Example

```html
<div class="dis-f f-wrap ac-center">
    ...
</div>
```

---

# Align Self

Override the alignment of a single flex item.

| Class | CSS |
|--------|---------------------------|
| as-auto | align-self: auto; |
| as-start | align-self: flex-start; |
| as-end | align-self: flex-end; |
| as-center | align-self: center; |
| as-baseline | align-self: baseline; |
| as-stretch | align-self: stretch; |

Example

```html
<div class="as-center">
    ...
</div>
```

---

# Flex Grow

Control how much an item grows.

| Class | CSS |
|--------|----------------|
| fg-0 | flex-grow: 0; |
| fg-1 | flex-grow: 1; |

Example

```html
<div class="fg-1">
    Flexible Item
</div>
```

---

# Flex Shrink

Control how much an item shrinks.

| Class | CSS |
|--------|------------------|
| fs-0 | flex-shrink: 0; |
| fs-1 | flex-shrink: 1; |

Example

```html
<div class="fs-0">
    Fixed Width Item
</div>
```

---

# Combining Utilities

Flex utilities are designed to work together.

Example

```html
<div class="dis-f f-row jc-between ai-center pd-4 shadow-md">

    <h2>Dashboard</h2>

    <button class="pd-2 br-md">
        Save
    </button>

</div>
```

---

# Best Practices

- Always use `dis-f` before applying Flex utilities.
- Use `jc-*` for horizontal alignment.
- Use `ai-*` for vertical alignment.
- Use `f-wrap` for responsive layouts.
- Combine utilities instead of writing custom Flexbox CSS.

---

# Common Layout Examples

### Center an Element

```html
<div class="dis-f jc-center ai-center">
    Centered Content
</div>
```

### Space Between Items

```html
<div class="dis-f jc-between ai-center">
    <span>Logo</span>
    <span>Menu</span>
</div>
```

### Vertical Layout

```html
<div class="dis-f f-col">
    <div>Header</div>
    <div>Content</div>
    <div>Footer</div>
</div>
```

---

# Related Utilities

- Display
- Grid
- Spacing
- Position
- Effects