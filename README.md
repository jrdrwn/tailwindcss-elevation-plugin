# TailwindCSS Elevation Plugin

Elevation style in Google Material Design for TailwindCSS

## Demo

[Elevation demo](https://jrdrwn.github.io/tailwindcss-elevation-plugin/)

## Usage

Install plugin

```bash
npm install tailwindcss-elevation-plugin
```

Import plugin to `tailwind.config.js`

```javascript
module.exports = {
  // Other configuration
  plugins: [require('tailwindcss-elevation-plugin')],
};
```

After that you can use it like this

```html
<h1 class="elevation-1">Hello World</h1>
<h1 class="elevation-1-dark">Hello World</h1>
```

## Custom Elevation

```javascript
module.exports = {
  // Other configuration
  elevation: {
    6: '0px 1px 2px rgba(0, 0, 0, 0.3), 0px 1px 3px 1px rgba(0, 0, 0, 0.15)'
  }
  plugins: [require('tailwindcss-elevation-plugin')],
};
```

If in css it will be like this

```css
.elevation-6 {
  box-shadow: px 1px 2px rgba(0, 0, 0, 0.3), 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
}
```

## Reference

- [MD Elevation](https://material.io/design/environment/elevation.html)

## License

[MIT](https://choosealicense.com/licenses/mit/)
