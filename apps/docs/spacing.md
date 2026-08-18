# Spacing

The **Spacing** utilities provide a consistent way to apply **margin** and **padding** throughout your application.

Instead of writing custom CSS, Uxiora offers predefined spacing utilities based on its design token system.

---

# Why Use Spacing Utilities?

Using spacing utilities helps you:

- Maintain consistent spacing
- Reduce custom CSS
- Build layouts faster
- Follow a predictable design system

---

# Spacing Scale

Uxiora uses a predefined spacing scale.

| Class | Value |
|--------|------:|
| 0 | 0px |
| 1 | 2px |
| 1.5 | 3px |
| 2 | 4px |
| 2.5 | 5px |
| 3 | 6px |
| 3.5 | 7px |
| 4 | 8px |
| ... | ... |

> The complete spacing scale is generated automatically from Uxiora's design tokens.

---

# Margin Utilities

Apply margin to all sides.

| Class | CSS |
|--------|-----|
| mg-1 | margin:2px; |
| mg-2 | margin:4px; |
| mg-4 | margin:8px; |

Example

```html
<div class="mg-4">
    Content
</div>
```

---

# Margin Top

| Class | CSS |
|--------|-----|
| mg-t-1 | margin-top:2px; |
| mg-t-2 | margin-top:4px; |

Example

```html
<div class="mg-t-4">
    Content
</div>
```

---

# Margin Right

| Class | CSS |
|--------|-----|
| mg-r-1 | margin-right:2px; |
| mg-r-2 | margin-right:4px; |

Example

```html
<div class="mg-r-4">
    Content
</div>
```

---

# Margin Bottom

| Class | CSS |
|--------|-----|
| mg-b-1 | margin-bottom:2px; |
| mg-b-2 | margin-bottom:4px; |

Example

```html
<div class="mg-b-4">
    Content
</div>
```

---

# Margin Left

| Class | CSS |
|--------|-----|
| mg-l-1 | margin-left:2px; |
| mg-l-2 | margin-left:4px; |

Example

```html
<div class="mg-l-4">
    Content
</div>
```

---

# Margin Inline

Applies margin to the inline direction.

| Class | CSS |
|--------|-----|
| mg-x-1 | margin-inline:2px; |
| mg-x-2 | margin-inline:4px; |

Example

```html
<div class="mg-x-4">
    Content
</div>
```

---

# Margin Block

Applies margin to the block direction.

| Class | CSS |
|--------|-----|
| mg-y-1 | margin-block:2px; |
| mg-y-2 | margin-block:4px; |

Example

```html
<div class="mg-y-4">
    Content
</div>
```

---

# Negative Margin

Negative margin utilities allow elements to move outside their normal spacing.

| Class | CSS |
|--------|-----|
| -mg-1 | margin:-2px; |
| -mg-2 | margin:-4px; |

Example

```html
<div class="-mg-4">
    Content
</div>
```

Use negative margins carefully to avoid layout issues.

---

# Padding Utilities

Apply padding to all sides.

| Class | CSS |
|--------|-----|
| pd-1 | padding:2px; |
| pd-2 | padding:4px; |
| pd-4 | padding:8px; |

Example

```html
<div class="pd-4">
    Content
</div>
```

---

# Padding Top

```html
<div class="pd-t-4">
    Content
</div>
```

---

# Padding Right

```html
<div class="pd-r-4">
    Content
</div>
```

---

# Padding Bottom

```html
<div class="pd-b-4">
    Content
</div>
```

---

# Padding Left

```html
<div class="pd-l-4">
    Content
</div>
```

---

# Padding Inline

```html
<div class="pd-x-4">
    Content
</div>
```

---

# Padding Block

```html
<div class="pd-y-4">
    Content
</div>
```

---

# Best Practices

- Use spacing utilities instead of custom margin and padding whenever possible.
- Keep spacing consistent throughout your project.
- Prefer `mg-x` and `pd-x` for horizontal spacing.
- Prefer `mg-y` and `pd-y` for vertical spacing.
- Avoid excessive negative margins unless required.

---

# Example Layout

```html
<div class="pd-6">

    <div class="mg-b-6">
        <h2>Dashboard</h2>
    </div>

    <div class="pd-4 shadow-md br-md">
        Welcome to Uxiora
    </div>

</div>
```

---

# Related Utilities

- Display
- Flex
- Grid
- Border
- Typography