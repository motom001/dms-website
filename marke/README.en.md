# Ablago – logo and colours

*[Deutsch](README.md)*

All versions of the Ablago logo live here. Every other repository (Ablago itself, manual, package catalog, app stores, clients) takes its logo and colours **from here**, so everything looks the same.

## Colours

| Name | Value | Use |
|---|---|---|
| Blue | `#1F4E79` | main colour, tile of the app icon |
| Accent | `#E8A33D` | the sheet in the logo, sparingly for highlights |
| Dark | `#141A22` | dark backgrounds |
| Blue in dark mode | `#2A6496` | only for the app icon on dark surfaces, not in the logo itself |
| Light text | `#E6ECF3` | text on dark backgrounds |

## Files

| File | Use |
|---|---|
| `ablago-app-blau.svg` | app icon, default (blue tile) |
| `ablago-app-dunkelmodus.svg` | app icon for dark surroundings (lighter blue) |
| `ablago-app-hell.svg` | white tile with border, for light surfaces |
| `ablago-zeichen-farbig.svg` | mark without tile (blue/orange), e.g. in an app header |
| `ablago-zeichen-einfarbig.svg` | mark in `currentColor`, slightly more space between sheet and tray |
| `ablago-homey-icon.svg` | Homey: single colour, transparent background (Homey adds its own colour) |
| `ablago-logo-mit-schriftzug.svg` | mark and “Ablago” wordmark for light backgrounds |
| `ablago-logo-mit-schriftzug-dunkel.svg` | the same for dark backgrounds |
| `favicon.svg`, `favicon.ico` | browser tab (ico with 16, 32 and 48 px) |
| `png/` | raster sizes 16–1024 px; 180 px = Apple touch icon, 192/512 px = web app manifest |

**Wordmark:** set in *Source Sans 3* (weight 600). Where the font is missing, the browser substitutes it. For print and fixed images, convert the text to paths first.

## Rules

- The name is **Ablago**: one word, only the A capitalised.
- Do not distort or recolour the logo (except the single-colour version), and do not combine it with other marks.
- Leave some space around the logo, at least one eighth of its width.
- App icon no smaller than 16 px, logo with wordmark no narrower than 120 px.
- Images need alternative text, usually “Ablago”.

## Rights

The code in this repository is licensed under the [Apache License 2.0](../LICENSE). **The Ablago name and logo are not covered** (section 6 of the licence, see [NOTICE](../NOTICE)).

You may refer to Ablago, e.g. “package for Ablago” or “runs on Ablago”, and show the unmodified logo when doing so. A fork or your own product needs its own name and logo.
