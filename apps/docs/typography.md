# Typography

The **Typography** utilities help you control the appearance of text using predefined utility classes.

Uxiora provides utilities for font size, font weight, font style, text alignment, text decoration, and text transformation, allowing you to create consistent typography without writing custom CSS.

---

# Why Use Typography Utilities?

Typography utilities help you:

- Maintain consistent text styles
- Improve readability
- Reduce custom CSS
- Build scalable user interfaces
- Follow a unified design system

---

# Font Size

Control the size of text.

| Class | CSS |
|--------|----------------|
| fs-xs | font-size |
| fs-sm | font-size |
| fs-md | font-size |
| fs-lg | font-size |
| fs-xl | font-size |
| fs-2xl | font-size |
| fs-3xl | font-size |

> The actual values are generated from Uxiora's design tokens.

Example

```html
<h1 class="fs-3xl">
    Uxiora
</h1>
```

---

# Font Weight

Control the thickness of text.

| Class | CSS |
|--------|----------------|
| fw-thin | font-weight |
| fw-light | font-weight |
| fw-normal | font-weight |
| fw-medium | font-weight |
| fw-semibold | font-weight |
| fw-bold | font-weight |
| fw-black | font-weight |

Example

```html
<p class="fw-bold">
    Bold Text
</p>
```

---

# Font Style

Control the style of text.

| Class | CSS |
|--------|----------------|
| fst-normal | font-style: normal; |
| fst-italic | font-style: italic; |
| fst-oblique | font-style: oblique; |

Example

```html
<p class="fst-italic">
    Italic Text
</p>
```

---

# Text Align

Align text horizontally.

| Class | CSS |
|--------|----------------|
| ta-start | text-align: start; |
| ta-end | text-align: end; |
| ta-left | text-align: left; |
| ta-center | text-align: center; |
| ta-right | text-align: right; |
| ta-justify | text-align: justify; |

Example

```html
<p class="ta-center">
    Centered Text
</p>
```

---

# Text Decoration

Apply text decoration styles.

| Class | CSS |
|--------|----------------|
| td-none | text-decoration: none; |
| td-underline | text-decoration: underline; |
| td-overline | text-decoration: overline; |
| td-line-through | text-decoration: line-through; |

Example

```html
<a class="td-none">
    Link
</a>
```

---

# Text Transform

Transform the case of text.

| Class | CSS |
|--------|----------------|
| tt-upper | text-transform: uppercase; |
| tt-lower | text-transform: lowercase; |
| tt-capitalize | text-transform: capitalize; |
| tt-none | text-transform: none; |

Example

```html
<p class="tt-upper">
    Uxiora Framework
</p>
```

---

# Combining Typography Utilities

Typography utilities are designed to work together.

Example

```html
<h2 class="fs-2xl fw-bold ta-center tt-capitalize">

    Welcome to Uxiora

</h2>
```

---

# Best Practices

- Use design token font sizes for consistency.
- Keep typography hierarchy clear.
- Use font weight to emphasize important content.
- Avoid excessive text transformations.
- Combine typography utilities instead of writing custom CSS.

---

# Common Examples

### Page Title

```html
<h1 class="fs-3xl fw-bold ta-center">

    Dashboard

</h1>
```

---

### Section Heading

```html
<h2 class="fs-xl fw-semibold">

    User Profile

</h2>
```

---

### Paragraph

```html
<p class="fs-md fw-normal">

    Uxiora helps you build modern interfaces faster.

</p>
```

---

### Link

```html
<a class="td-none fw-medium">

    Learn More

</a>
```

---

# Related Utilities

- Display
- Flex
- Grid
- Border
- Effects
