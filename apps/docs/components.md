# Components

Components are planned for a future release of **Uxiora**.

The first major release (**v1.0.0**) focuses on providing a stable, lightweight, and consistent CSS utility framework.

Once the core framework is stable, reusable UI components will be introduced in future versions.

---

# Why Components Are Not Included in Version 1

The goal of Version 1 is to build a strong foundation.

Before creating reusable UI components, the following must be stable:

- Helpers
- Foundation
- Utilities
- Design Tokens
- Documentation

A stable foundation ensures every future component is built on a consistent design system.

---

# Future Component Library

Future releases of Uxiora may include the following components.

## Buttons

```html
<ux-button>
    Button
</ux-button>
```

---

## Cards

```html
<ux-card>

    Card Content

</ux-card>
```

---

## Inputs

```html
<ux-input
    placeholder="Enter your name"
/>
```

---

## Forms

- Text Field
- Textarea
- Select
- Checkbox
- Radio
- Switch

---

## Navigation

- Navbar
- Sidebar
- Breadcrumb
- Pagination
- Tabs

---

## Feedback

- Alert
- Badge
- Toast
- Modal
- Tooltip
- Progress

---

## Data Display

- Avatar
- Table
- Timeline
- Accordion
- List Group

---

## Layout

- Container
- Stack
- Grid Components
- Divider

---

# React Components

After the CSS framework reaches a stable release, Uxiora will introduce an official React package.

Example

```jsx
import { Button } from "@uxiora/react";

function App() {
    return (
        <Button>
            Get Started
        </Button>
    );
}
```

The React package will be built using the same design tokens and utility system as the CSS framework.

---

# Design Principles

Every Uxiora component will follow these principles.

- Accessible by default
- Lightweight
- Reusable
- Customizable
- Consistent
- Easy to use
- Production ready

---

# Roadmap

Version 1

- CSS Framework
- Documentation
- Utilities
- Design Tokens

Version 2

- React Components
- Themes
- Icons Integration
- Advanced Utilities

Version 3

- CLI
- Templates
- Starter Kits
- Plugin Ecosystem

---

# Our Philosophy

Uxiora follows a simple philosophy.

**Build a strong foundation first.**

A well-designed utility framework makes it easier to build reliable components in future releases.

Instead of rushing to add hundreds of components, Uxiora focuses on quality, consistency, and long-term maintainability.

---
