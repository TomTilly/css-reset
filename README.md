# Tilly's CSS Reset

This is my simple CSS reset, which is a mix between [Andy Bell](https://piccalil.li/blog/a-modern-css-reset/) and [Josh Comeau's](https://www.joshwcomeau.com/css/custom-css-reset/) awesome resets, with one of my own rules thrown in.

## Usage

1. Install with `npm install tillys-css-reset`
2. Link to the stylesheet in your HTML

```html
<link rel="stylesheet" href="./node_modules/tillys-css-reset/dist/reset.css" />
<!-- or if you prefer minified CSS  -->
<link
  rel="stylesheet"
  href="./node_modules/tillys-css-reset/dist/reset.min.css"
/>
```

If you're using a bundler with a CSS loader, you can import directly in your JS:

```js
import css from 'tillys-css-reset/dist/reset.min.css';
```

You can also import it via CSS/SCSS:

```css
@import './node_modules/tillys-css-reset/dist/reset.min.css';
```
