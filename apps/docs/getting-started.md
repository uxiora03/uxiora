# Getting Started

Welcome to **Uxiora**, a modern, lightweight, utility-first CSS framework built with SCSS.

Uxiora is designed to help developers build clean, consistent, and responsive user interfaces with a simple and predictable utility API.

---

# Why Uxiora?

Uxiora focuses on developer experience by providing:

- Lightweight CSS output
- Modern CSS utilities
- Design Token architecture
- Consistent naming conventions
- Utility-first workflow
- SCSS-powered architecture
- Easy customization
- Scalable project structure

Whether you're building a landing page, dashboard, portfolio, or enterprise application, Uxiora helps you build faster with less custom CSS.

---

# Requirements

Before using Uxiora, make sure you have one of the following:

- HTML
- React
- Vue
- Angular
- Next.js
- Vite
- Any modern frontend project

---

# Installation

Install Uxiora using npm.

```bash
npm install uxiora
```

Import the CSS file into your project.

```javascript
import "uxiora/dist/uxiora.css";
```

You can also include the compiled CSS directly in HTML.

```html
<link rel="stylesheet" href="uxiora.css">
```

---

# Your First Example

```html
<div class="dis-f jc-center ai-center pd-4 shadow-md br-md">
    Welcome to Uxiora
</div>
```

---

# Project Philosophy

Uxiora follows a utility-first approach.

Instead of writing custom CSS for every component, combine small utility classes to build layouts quickly.

Example:

```html
<div class="dis-f jc-between ai-center pd-4">
    <h2>Dashboard</h2>

    <button class="pd-2 shadow-sm">
        Save
    </button>
</div>
```

---

# Folder Structure

The CSS package is organized into three main modules.

```
src/

├── foundation/
├── helpers/
└── utilities/
```

## Helpers

Contains design tokens, maps, functions, and mixins used throughout the framework.

## Foundation

Provides CSS reset, root variables, and base styles.

## Utilities

Contains reusable utility classes for spacing, display, flexbox, grid, borders, typography, effects, and more.

---

# Documentation

The documentation is organized into multiple sections.

- Installation
- Utilities
- Spacing
- Display
- Flex
- Grid
- Border
- Typography
- Effects

Each page includes examples and usage guidelines.

---

# Browser Support

Uxiora is designed for modern browsers that support CSS Custom Properties and modern layout features such as Flexbox and Grid.

---

# Version

Current Version

```
v1.0.0
```

---

# License

Uxiora is released under the MIT License.