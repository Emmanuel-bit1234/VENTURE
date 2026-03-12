# A K Barber Shop Northcliff

A modern, responsive website for **A K Barber Shop Northcliff** — a barbershop in Blackheath, Johannesburg, serving Northcliff and the surrounding area.

**Tagline:** Professional cuts for men, kids, and ladies.

---

## About the business

- **Location:** 244 Beyers Naudé Dr, Blackheath, 2195 (opposite Engen Mimosa, near Cresta Shopping Centre)
- **Area served:** Northcliff
- **Hours:** Open — closes at 6:00 PM
- **Phone:** 067 031 3818

---

## Tech stack

- **HTML5** — semantic structure, accessibility-friendly
- **CSS3** — layout, typography, responsive design, dark theme
- **Vanilla JavaScript** — mobile menu toggle (hamburger ↔ cross), footer year, smooth behaviour

No frameworks or build step. Open the HTML file in a browser or host the folder on any static host.

---

## Features

- **Hero** — Business name, tagline, intro, Call Now & Find Us buttons
- **About** — Short welcome and service overview (men, kids, ladies)
- **Our Space** — Image gallery
- **Services** — Cards for: Men’s haircuts, fades, blade fades, school haircuts for kids, ladies’ haircuts, eyebrow threading, ladies’ hair colouring, facials
- **Why Choose Us** — Professional service, location, family-friendly, quality grooming
- **Contact** — Phone, address, area, hours, call-to-action button
- **Footer** — Name, tagline, contact, copyright

Responsive layout with a mobile-first feel: hamburger menu that turns into a cross when open, touch-friendly buttons, and safe-area support for notched devices.

---

## How to run

1. Clone or download this folder.
2. Open `index.html` in a web browser (double-click or drag into the browser window).

To serve locally (optional):

```bash
# Python 3
python3 -m http.server 8000

# Then open http://localhost:8000
```

---

## Project structure

```
VENTURE/
├── index.html    # Main page markup
├── styles.css    # All styles (variables, layout, responsive, components)
└── README.md     # This file
```

---

## Customisation

- **Colours:** Edit CSS variables in `:root` in `styles.css` (e.g. `--color-accent`, `--color-bg`).
- **Content:** Update text, phone number, address, and hours in `index.html`.
- **Images:** Replace Unsplash URLs in `index.html` with your own image paths; service cards use `onerror` fallbacks if an image fails to load.

---

## Licence

Website code can be used and modified as needed. Stock images are from [Unsplash](https://unsplash.com); check their licence for image use.
