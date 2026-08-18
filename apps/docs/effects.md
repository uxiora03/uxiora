# Effects

The **Effects** utilities provide reusable visual enhancement classes for your user interface.

Uxiora includes utilities for opacity, shadows, transitions, pointer events, and user selection, allowing you to create interactive and polished interfaces without writing custom CSS.

---

# Why Use Effects Utilities?

Effects utilities help you:

- Improve visual appearance
- Create interactive user experiences
- Reduce repetitive CSS
- Keep designs consistent
- Build modern user interfaces faster

---

# Opacity

Control the transparency of an element.

| Class | CSS |
|--------|----------------|
| op-0 | opacity: 0; |
| op-25 | opacity: 0.25; |
| op-50 | opacity: 0.5; |
| op-75 | opacity: 0.75; |
| op-100 | opacity: 1; |

Example

```html
<div class="op-50">
    Semi Transparent
</div>
```

---

# Box Shadow

Apply predefined shadow styles.

| Class | Description |
|--------|-------------|
| shadow-none | No shadow |
| shadow-sm | Small shadow |
| shadow-md | Medium shadow |
| shadow-lg | Large shadow |
| shadow-xl | Extra large shadow |

Example

```html
<div class="shadow-lg pd-4 br-lg">

    Uxiora Card

</div>
```

---

# Transition

Apply predefined transition effects.

| Class | Description |
|--------|-------------|
| trans | Default transition |
| trans-none | Disable transition |
| trans-fast | Fast transition |
| trans-normal | Normal transition |
| trans-slow | Slow transition |

Example

```html
<button class="trans shadow-sm">

    Hover Me

</button>
```

---

# Pointer Events

Control whether an element responds to mouse interactions.

| Class | CSS |
|--------|----------------|
| pe-auto | pointer-events: auto; |
| pe-none | pointer-events: none; |

Example

```html
<button class="pe-none">

    Disabled Click

</button>
```

---

# User Select

Control whether text can be selected.

| Class | CSS |
|--------|----------------|
| select-auto | user-select: auto; |
| select-none | user-select: none; |
| select-text | user-select: text; |
| select-all | user-select: all; |

Example

```html
<p class="select-none">

    This text cannot be selected.

</p>
```

---

# Combining Effects

Effects utilities are designed to work together.

Example

```html
<div class="shadow-lg trans br-lg pd-6">

    Welcome to Uxiora

</div>
```

---

# Best Practices

- Use shadows consistently across your application.
- Apply transitions only where user interaction is expected.
- Use opacity to indicate disabled or secondary content.
- Use pointer event utilities carefully.
- Prevent text selection only when necessary.

---

# Common Examples

### Card

```html
<div class="shadow-md br-lg pd-4">

    Card Content

</div>
```

---

### Hover Button

```html
<button class="shadow-sm trans">

    Submit

</button>
```

---

### Disabled Element

```html
<button class="op-50 pe-none">

    Disabled

</button>
```

---

### Non-selectable Text

```html
<p class="select-none">

    Copyright © Uxiora

</p>
```

---

# Related Utilities

- Border
- Typography
- Display
- Flex
- Grid

---