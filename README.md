<div align="center">

# Unit Convert

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen?style=flat-square)](https://soumendrak.github.io/unit-convert/)
[![MIT License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-%23E34F26?style=flat-square&logo=html5&logoColor=white)](https://html.spec.whatwg.org/)
[![Zero Dependencies](https://img.shields.io/badge/dependencies-0-success?style=flat-square)](https://www.w3.org/TR/html52/)

<!-- Inline SVG logo -->
<svg width="140" height="140" viewBox="0 0 140 140" xmlns="http://www.w3.org/2000/svg">
<rect width="140" height="140" rx="24" fill="#0a0a14"/>
  <rect x="16" y="28" width="108" height="24" rx="6" fill="#1a1a2e"/>
  <text x="70" y="44" text-anchor="middle" font-family="sans-serif" font-size="9" fill="#f0ece4">°C  °F  K</text>
  <text x="70" y="78" text-anchor="middle" font-family="monospace" font-size="22" font-weight="bold" fill="#ff6b35">100</text>
  <text x="70" y="96" text-anchor="middle" font-family="monospace" font-size="14" fill="#f0ece4">212 °F</text>
  <rect x="16" y="110" width="108" height="2" rx="1" fill="#2a2a2a"/>
  <text x="70" y="128" text-anchor="middle" font-family="sans-serif" font-size="8" fill="#5a5a6e">m · km · ft · mi · kg · lb</text>
</svg>

**Convert between units of temperature, length, weight, area, and volume — live.**

**Live:** [https://soumendrak.github.io/unit-convert/](https://soumendrak.github.io/unit-convert/)

</div>

---

## Features

- 5 category tabs: Temperature, Length, Weight, Area, Volume
- 35+ units across all categories
- Live conversion as you type — no button press needed
- Swap button to instantly exchange source/target units
- Clean tabbed interface with smooth transitions
- Dark theme with orange accent (#ff6b35)

## How It Works

Each category has a conversion factors object mapping unit → base unit. When the user types a value, it's converted to the base unit, then to the target unit using conversion factors. Temperature uses formula-based conversion (C × 9/5 + 32, C + 273.15, etc.). The Swap button exchanges source and target selectors and re-runs the conversion.

## Usage

1. Open `https://soumendrak.github.io/unit-convert/` in any browser.
2. No build step, no installation, no server required.
3. Deploy anywhere — GitHub Pages, Netlify, or any static host.

```bash
git clone https://github.com/soumendrak/unit-convert.git
# Open index.html directly
```

## License

Licensed under the [MIT License](LICENSE).

---

<p align="center"><sub>Built with ❤️ and zero dependencies</sub></p>
