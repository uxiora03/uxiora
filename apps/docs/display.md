# Display

The **Display** utilities control how an element is rendered in the document layout.

Uxiora provides a collection of display utilities that make it easy to switch between block, inline, flex, grid, table, and other display modes without writing custom CSS.

---

# Why Use Display Utilities?

Display utilities help you:

- Build layouts faster
- Switch between layout modes
- Reduce custom CSS
- Create responsive user interfaces
- Keep your HTML clean and consistent

---

# Available Classes

| Class | CSS |
|--------|-------------------------|
| dis-b | display: block; |
| dis-i | display: inline; |
| dis-ib | display: inline-block; |
| dis-f | display: flex; |
| dis-if | display: inline-flex; |
| dis-g | display: grid; |
| dis-ig | display: inline-grid; |
| dis-t | display: table; |
| dis-tr | display: table-row; |
| dis-tc | display: table-cell; |
| dis-tco | display: table-column; |
| dis-tca | display: table-caption; |
| dis-li | display: list-item; |
| dis-fr | display: flow-root; |
| dis-con | display: contents; |
| dis-n | display: none; |
| dis-inh | display: inherit; |
| dis-ini | display: initial; |
| dis-u | display: unset; |

---

# Block

A block element starts on a new line and takes the full available width.

```html
<div class="dis-b">
    Block Element
</div>
```

---

# Inline

An inline element only takes the width of its content.

```html
<span class="dis-i">
    Inline Element
</span>
```

---

# Inline Block

Behaves like an inline element but allows width and height.

```html
<div class="dis-ib">
    Inline Block
</div>
```

---

# Flex

Creates a Flexbox container.

```html
<div class="dis-f">
    ...
</div>
```

Flex utilities work perfectly with:

- `f-row`
- `f-col`
- `jc-center`
- `ai-center`

---

# Inline Flex

Creates an inline flex container.

```html
<div class="dis-if">
    ...
</div>
```

---

# Grid

Creates a CSS Grid container.

```html
<div class="dis-g">
    ...
</div>
```

Grid utilities work well with:

- `js-center`
- `ji-center`
- `pi-center`
- `pc-center`
- `ps-center`

---

# Inline Grid

```html
<div class="dis-ig">
    ...
</div>
```

---

# Table Utilities

Uxiora also supports table display values.

```html
<div class="dis-t">
```

```html
<div class="dis-tr">
```

```html
<div class="dis-tc">
```

Useful when creating table-like layouts without using actual table elements.

---

# Flow Root

Creates a new block formatting context.

```html
<div class="dis-fr">
```

This is useful for clearing floated elements and preventing margin collapsing.

---

# Contents

```html
<div class="dis-con">
```

The wrapper element is ignored during layout while its children remain visible.

Use this utility carefully, as browser support and accessibility behavior may vary.

---

# None

Hide an element completely.

```html
<div class="dis-n">
```

Equivalent to:

```css
display: none;
```

---

# Inherit

```html
<div class="dis-inh">
```

Inherits the display value from the parent element.

---

# Initial

```html
<div class="dis-ini">
```

Resets the display property to its default value.

---

# Unset

```html
<div class="dis-u">
```

Removes the assigned display value and lets CSS determine the final result.

---

# Best Practices

- Use `dis-f` for Flexbox layouts.
- Use `dis-g` for Grid layouts.
- Use `dis-b` for block-level elements.
- Use `dis-i` for inline elements.
- Use `dis-n` to hide elements.
- Avoid changing display values unnecessarily.

---

# Example

```html
<div class="dis-f jc-between ai-center pd-4 shadow-md">

    <h2>Uxiora</h2>

    <button class="pd-2">
        Get Started
    </button>

</div>
```

---

# Related Utilities

- Flex
- Grid
- Visibility
- Overflow
- Position