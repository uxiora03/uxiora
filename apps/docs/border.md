# Border

The **Border** utilities allow you to control border width, border radius, border style, and outline using predefined utility classes.

Instead of writing custom CSS, Uxiora provides a consistent set of border utilities that work across all projects.

---

# Why Use Border Utilities?

Border utilities help you:

- Create consistent borders
- Build reusable UI components
- Reduce custom CSS
- Keep designs visually consistent
- Speed up development

---

# Border Width

Apply border width to all sides.

| Class | CSS |
|--------|----------------|
| bor-0 | border-width: 0; |
| bor-1 | border-width: 1px; |
| bor-2 | border-width: 2px; |
| bor-3 | border-width: 3px; |
| bor-4 | border-width: 4px; |

Example

```html
<div class="bor-2">
    Border Width
</div>
```

---

# Border Top

Apply border width to the top.

| Class | CSS |
|--------|---------------------|
| bor-t-1 | border-top-width: 1px; |
| bor-t-2 | border-top-width: 2px; |

Example

```html
<div class="bor-t-2">
    Border Top
</div>
```

---

# Border Right

Apply border width to the right.

| Class | CSS |
|--------|----------------------|
| bor-r-1 | border-right-width: 1px; |
| bor-r-2 | border-right-width: 2px; |

Example

```html
<div class="bor-r-2">
    Border Right
</div>
```

---

# Border Bottom

Apply border width to the bottom.

| Class | CSS |
|--------|-----------------------|
| bor-b-1 | border-bottom-width: 1px; |
| bor-b-2 | border-bottom-width: 2px; |

Example

```html
<div class="bor-b-2">
    Border Bottom
</div>
```

---

# Border Left

Apply border width to the left.

| Class | CSS |
|--------|----------------------|
| bor-l-1 | border-left-width: 1px; |
| bor-l-2 | border-left-width: 2px; |

Example

```html
<div class="bor-l-2">
    Border Left
</div>
```

---

# Border Inline

Apply border width to the inline direction.

| Class | CSS |
|--------|-------------------------|
| bor-x-1 | border-inline-width: 1px; |
| bor-x-2 | border-inline-width: 2px; |

Example

```html
<div class="bor-x-2">
    Border Inline
</div>
```

---

# Border Block

Apply border width to the block direction.

| Class | CSS |
|--------|------------------------|
| bor-y-1 | border-block-width: 1px; |
| bor-y-2 | border-block-width: 2px; |

Example

```html
<div class="bor-y-2">
    Border Block
</div>
```

---

# Border Radius

Border radius utilities create rounded corners.

| Class | CSS |
|--------|----------------|
| br-none | border-radius: 0; |
| br-sm | Small radius |
| br-md | Medium radius |
| br-lg | Large radius |
| br-xl | Extra large radius |
| br-full | Fully rounded |

Example

```html
<div class="br-lg">
    Rounded Card
</div>
```

---

# Border Style

Control the border style.

| Class | CSS |
|--------|----------------|
| bs-solid | border-style: solid; |
| bs-dashed | border-style: dashed; |
| bs-dotted | border-style: dotted; |
| bs-double | border-style: double; |
| bs-hidden | border-style: hidden; |
| bs-none | border-style: none; |

Example

```html
<div class="bor-2 bs-solid">
    Solid Border
</div>
```

---

# Outline

Outline utilities apply an outline around an element.

| Class | CSS |
|--------|----------------|
| out-0 | outline-width: 0; |
| out-1 | outline-width: 1px; |
| out-2 | outline-width: 2px; |
| out-3 | outline-width: 3px; |

Example

```html
<div class="out-2">
    Outline Example
</div>
```

---

# Combining Border Utilities

Border utilities are designed to work together.

Example

```html
<div class="bor-2 bs-solid br-lg shadow-md pd-4">

    Uxiora Card

</div>
```

---

# Best Practices

- Use consistent border widths across your project.
- Combine border width with border style.
- Use border radius to create modern UI components.
- Use outline for focus states and accessibility.
- Prefer utility classes over custom CSS whenever possible.

---

# Common Examples

### Card

```html
<div class="bor-1 bs-solid br-lg pd-4 shadow-sm">

    Card Content

</div>
```

---

### Rounded Button

```html
<button class="bor-1 bs-solid br-full pd-2">

    Click Me

</button>
```

---

### Input Field

```html
<input
    class="bor-1 bs-solid br-md pd-2"
    placeholder="Username"
/>
```

---

# Related Utilities

- Spacing
- Display
- Flex
- Grid
- Effects