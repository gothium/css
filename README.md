[![NPM Version](https://img.shields.io/npm/v/@gothium/css)](https://www.npmjs.com/package/@gothium/css)

# Gothium CSS Reset

Gothium CSS is a modern, lightweight CSS Framework designed to normalize styles and provide a consistent styling and responsiveness for your projects. It uses best practices, avoids outdated hacks, and leverages inheritance to reduce boilerplate code, offering powerful defaults via new technologies; [fluid type and space scaling | utopia.fyi ](https://utopia.fyi/) + [CSS Custom Variables](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_cascading_variables/Using_CSS_custom_properties) for themes in addition [prefered color scheme with only CSS](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-color-scheme).

## Features

- **Modern**: Uses up-to-date best practices.
- **Lightweight**: Minimal code with powerful effects.
- **Effortless**: Simplifies cross-browser compatibility.
- **Efficient**: Reduces boilerplate code with smart defaults.

## Development & Contributing

You can install the [zola](https://github.com/getzola/zola) then run the `zola build` or `prepare` script on `package.json`.

## Installation and Usage

You can install and build the Gothium CSS using various package managers. Below are the instructions for each:

### UNPKG (via CDN)

#### In HTML

```html
<link rel="stylesheet" href="https://unpkg.com/@gothium/css">
```

#### In CSS

```css
@import 'https://unpkg.com/@gothium/css';
```

### via Package Manager

```sh
# Using Bun
bun add @gothium/css

# Using npm
npm install @gothium/css

# Using pnpm
pnpm add @gothium/css

# Using Yarn
yarn add @gothium/css

# Using Deno
deno install @gothium/css
```

#### Usage

```js
import '@gothium/css';
```

## License

This project is licensed under the MIT License.
