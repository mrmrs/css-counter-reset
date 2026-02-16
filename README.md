# css-counter-reset

Functional CSS for counter-reset

## Filesize

| File | Size |
|------|------|
| `dist/counter-reset.css` | 805 bytes |
| `dist/counter-reset.min.css` | 575 bytes (167 Gzipped) |

## Install

```sh
npm install css-counter-reset
```

## Usage

### Import

```css
@import "css-counter-reset";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-counter-reset/dist/counter-reset.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-counter-reset/dist/counter-reset.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.cr` | `counter-reset: count;` |
| `.cr-minus` | `counter-reset: count -1;` |
| `.cr-none` | `counter-reset: none;` |
| `.cr-i` | `counter-reset: inherit;` |
| `.cr-s` | `counter-reset: count;` |
| `.cr-minus-s` | `counter-reset: count -1;` |
| `.cr-none-s` | `counter-reset: none;` |
| `.cr-i-s` | `counter-reset: inherit;` |
| `.cr-m` | `counter-reset: count;` |
| `.cr-minus-m` | `counter-reset: count -1;` |
| `.cr-none-m` | `counter-reset: none;` |
| `.cr-i-m` | `counter-reset: inherit;` |
| `.cr-l` | `counter-reset: count;` |
| `.cr-minus-l` | `counter-reset: count -1;` |
| `.cr-none-l` | `counter-reset: none;` |
| `.cr-i-l` | `counter-reset: inherit;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.cr-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/counter-reset.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/counter-reset.css` — formatted
- `dist/counter-reset.min.css` — minified

## License

MIT
