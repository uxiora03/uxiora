# Installation

This guide explains how to install and start using **Uxiora** in your project.

---

# Requirements

Before installing Uxiora, make sure your project uses one of the following environments:

- HTML
- Vite
- React
- Next.js
- Vue
- Angular
- Any project that supports CSS imports

---

# Install Using npm

Install the latest version of Uxiora using npm.

```bash
npm install uxiora
```

Using pnpm:

```bash
pnpm add uxiora
```

Using Yarn:

```bash
yarn add uxiora
```

---

# Import CSS

After installation, import the compiled CSS file into your project.

```javascript
import "uxiora/dist/uxiora.css";
```

---

# HTML Usage

If you're using plain HTML, include the compiled CSS file.

```html
<link rel="stylesheet" href="uxiora.css">
```

---

# Verify Installation

Create a simple HTML element using Uxiora utility classes.

```html
<div class="dis-f jc-center ai-center pd-4 shadow-md br-md">
    Uxiora Installed Successfully 🎉
</div>
```

If the content is centered and styled correctly, Uxiora has been installed successfully.

---

# React Example

```jsx
function App() {
    return (
        <div className="dis-f jc-center ai-center pd-4 shadow-md br-md">
            Welcome to Uxiora
        </div>
    );
}

export default App;
```

---

# Recommended Project Structure

```
src/
├── components/
├── pages/
├── styles/
└── App.jsx
```

Import Uxiora once in your application's entry file.

Example:

```javascript
import "uxiora/dist/uxiora.css";
```

---

# Updating Uxiora

To update to the latest version, run:

```bash
npm update uxiora
```

or

```bash
pnpm update uxiora
```

---

# Uninstall

To remove Uxiora from your project:

```bash
npm uninstall uxiora
```

or

```bash
pnpm remove uxiora
```

---

# Troubleshooting

## CSS is not loading

Make sure you imported the CSS file.

```javascript
import "uxiora/dist/uxiora.css";
```

---

## Utility classes are not working

Check that:

- Uxiora is installed successfully.
- The CSS file is imported.
- The class names are spelled correctly.
- Your build tool includes CSS imports.