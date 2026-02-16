# css-text-rendering

Functional CSS for text-rendering

## Filesize

| File | Size |
|------|------|
| `dist/text-rendering.css` | 1213 bytes |
| `dist/text-rendering.min.css` | 929 bytes (207 Gzipped) |

## Install

```sh
npm install css-text-rendering
```

## Usage

### Import

```css
@import "css-text-rendering";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-text-rendering/dist/text-rendering.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-text-rendering/dist/text-rendering.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.txtr-auto` | `text-rendering: auto;` |
| `.txtr-speed` | `text-rendering: optimizespeed;` |
| `.txtr-legibile` | `text-rendering: optimizelegibility;` |
| `.txtr-precise` | `text-rendering: geometricprecision;` |
| `.txtr-i` | `text-rendering: inherit;` |
| `.txtr-auto-s` | `text-rendering: auto;` |
| `.txtr-speed-s` | `text-rendering: optimizespeed;` |
| `.txtr-legibile-s` | `text-rendering: optimizelegibility;` |
| `.txtr-precise-s` | `text-rendering: geometricprecision;` |
| `.txtr-i-s` | `text-rendering: inherit;` |
| `.txtr-auto-m` | `text-rendering: auto;` |
| `.txtr-speed-m` | `text-rendering: optimizespeed;` |
| `.txtr-legibile-m` | `text-rendering: optimizelegibility;` |
| `.txtr-precise-m` | `text-rendering: geometricprecision;` |
| `.txtr-i-m` | `text-rendering: inherit;` |
| `.txtr-auto-l` | `text-rendering: auto;` |
| `.txtr-speed-l` | `text-rendering: optimizespeed;` |
| `.txtr-legibile-l` | `text-rendering: optimizelegibility;` |
| `.txtr-precise-l` | `text-rendering: geometricprecision;` |
| `.txtr-i-l` | `text-rendering: inherit;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.txtr-auto-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/text-rendering.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/text-rendering.css` — formatted
- `dist/text-rendering.min.css` — minified

## License

MIT
