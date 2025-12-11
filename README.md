# Hashicons

[![npm version](https://img.shields.io/npm/v/hashicons.svg)](https://www.npmjs.com/package/hashicons)
[![npm downloads](https://img.shields.io/npm/dt/hashicons.svg)](https://www.npmjs.com/package/hashicons)
[![license](https://img.shields.io/npm/l/hashicons.svg)](LICENSE)

> Free 16px icon set with SVG files and web fonts (TTF, WOFF, WOFF2, EOT) - Clean, minimal, and ready-to-use icons for web projects.

A carefully crafted 16px-based icon set designed for modern web interfaces. Available in multiple formats for maximum flexibility.

## Features

- ✅ **16px optimized** - Crisp at any scale
- ✅ **Multiple formats** - SVG, TTF, WOFF, WOFF2, EOT
- ✅ **Web fonts** - Ready-to-use @font-face CSS
- ✅ **SVG sprite** - Single file for all icons
- ✅ **JSON metadata** - Programmatic access
- ✅ **Free & open source** - MIT licensed
- ✅ **Zero dependencies** - Pure icon assets

## Installation

### NPM

```bash
npm install hashicons
```

### Yarn

```bash
yarn add hashicons
```

### CDN

Use via unpkg or jsdelivr:

```html
<!-- CSS -->
<link rel="stylesheet" href="https://unpkg.com/hashicons/font/hashicons.css">

<!-- Icon usage -->
<i class="hi hi-home"></i>
```

## Usage

### Web Fonts

Include the CSS file and use icon classes:

```html
<link rel="stylesheet" href="node_modules/hashicons/font/hashicons.css">

<!-- Basic usage -->
<i class="hi hi-home"></i>
<i class="hi hi-user"></i>
<i class="hi hi-heart"></i>

<!-- With size -->
<i class="hi hi-star" style="font-size: 24px;"></i>
```

### SVG Files

Import individual SVG files:

```html
<img src="node_modules/hashicons/svg/home.svg" alt="Home">
```

### SVG Sprite

Use the sprite for optimal loading:

```html
<svg>
  <use href="node_modules/hashicons/sprite/hashicons.svg#home"></use>
</svg>
```

### JSON Metadata

Access icon data programmatically:

```javascript
const icons = require('hashicons/json/hashicons.json');

console.log(icons);
// {
//   "name": "hashicons",
//   "icons": {
//     "home": { "unicode": 57600, "hex": "e100" },
//     "user": { "unicode": 57601, "hex": "e101" }
//   }
// }
```

## File Structure

```
hashicons/
├── font/           # Web fonts (TTF, WOFF, WOFF2, EOT)
│   ├── hashicons.css
│   ├── hashicons.ttf
│   ├── hashicons.woff
│   ├── hashicons.woff2
│   └── hashicons.eot
├── svg/            # Individual SVG files
├── sprite/         # SVG sprite
│   └── hashicons.svg
└── json/           # Icon metadata
    └── hashicons.json
```

## Requirements

- No runtime dependencies
- Node.js >= 12.0.0 (for npm installation only)

## Changelog

### v1.0.2 (2025)

- 🚀 Updated package description for better SEO
- 🚀 Enhanced keywords for npm discoverability
- 📚 Improved README with usage examples and features
- 🔧 Fixed UTF-8 encoding issues

### v1.0.1 (Previous)

- Initial release

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

MIT License - see the [LICENSE](LICENSE) file for details.

## Author

**Orçun Saltık**

- GitHub: [@orcunsaltik](https://github.com/orcunsaltik)
- Email: saltikorcun@gmail.com

---

Made with ❤️ for the web community