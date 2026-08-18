# Utilities

Uxiora provides a comprehensive set of utility classes that help you build modern user interfaces without writing custom CSS.

Utility classes are small, reusable CSS classes that apply a single style or behavior to an element. By combining multiple utilities, you can create complex layouts quickly while keeping your HTML clean and consistent.

---

# Why Use Utilities?

Uxiora utilities are designed to be:

- Lightweight
- Reusable
- Predictable
- Easy to learn
- Easy to maintain
- Consistent across projects

Instead of writing custom CSS repeatedly, use utility classes to speed up development.

---

# Utility Categories

Uxiora is organized into the following utility modules.

| Module | Description |
|----------|-------------|
| Spacing | Margin and padding utilities |
| Display | Display property utilities |
| Visibility | Visibility helpers |
| Overflow | Overflow control utilities |
| Flex | Flexbox layout utilities |
| Grid | CSS Grid alignment utilities |
| Position | Position utilities |
| Border | Border width utilities |
| Border Radius | Border radius utilities |
| Border Style | Border style utilities |
| Outline | Outline width utilities |
| Typography | Font size, weight, style, alignment, decoration and transformation |
| Cursor | Cursor utilities |
| Effects | Shadow, opacity, transition, pointer events and user selection |

---

# Utility Naming Convention

Uxiora uses short, predictable class names.

Examples:

```text
mg-4
pd-3

dis-f

jc-center
ai-center

f-row

js-center
pi-center

bor-2

br-md

fs-lg

fw-bold

cur-pointer

shadow-lg
```

Each utility follows a consistent naming pattern, making it easy to remember and use.

---

# Example

```html
<div class="dis-f jc-center ai-center pd-4 shadow-md br-md">
    Welcome to Uxiora
</div>
```

The above example combines multiple utilities to create a centered card without writing any custom CSS.

---

# Utility Philosophy

Each utility is designed with a single responsibility.

Instead of creating large CSS components, Uxiora encourages combining small utility classes to build flexible layouts.

Example:

```html
<div class="dis-g pi-center pd-5 shadow-lg br-lg">
    Card Content
</div>
```

This approach keeps your UI consistent and reduces repetitive CSS.

---

# Best Practices

- Combine multiple utilities to build layouts.
- Prefer utility classes over custom CSS whenever possible.
- Keep your HTML readable by using meaningful combinations of utilities.
- Follow the documented utility names for consistency.
- Use design token values provided by Uxiora instead of hardcoded values.

---

# Available Documentation

Continue reading the following guides to learn each utility module.

- Spacing
- Display
- Visibility
- Overflow
- Flex
- Grid
- Position
- Border
- Border Radius
- Border Style
- Outline
- Typography
- Cursor
- Effects

Each guide includes available classes, examples and best practices.