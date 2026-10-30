# ExifCleaner assets: which file to use

Open `index.html` in a browser for previews. Version 2.0, 29 October 2026.

## Website header, documents and slides on a light ground

- `logo/exifcleaner-lockup-light.svg`

## The same on Deep Teal or another dark ground

- `logo/exifcleaner-lockup-dark.svg`

## One-color printing, engraving, embroidery

- `logo/exifcleaner-lockup-mono-deep-teal.svg`
- `logo/exifcleaner-lockup-mono-white.svg`

## The symbol alone: avatars, stickers, small spaces

- `logo/exifcleaner-symbol-light.svg`
- `logo/exifcleaner-symbol-dark.svg`
- `logo/exifcleaner-symbol-mono-deep-teal.svg`

## 24 px and below

- `logo/exifcleaner-symbol-small-light.svg`
- `logo/exifcleaner-symbol-small-dark.svg`

## macOS app icon (.icns source, Apple’s template margin)

- `icon/exifcleaner-icon-macos-1024.png`
- `icon/exifcleaner-icon-macos.svg`

## Full-bleed icon master (newer icon tools apply the shape)

- `icon/exifcleaner-icon-full-bleed-1024.png`
- `icon/exifcleaner-icon-full-bleed.svg`

## Windows and Linux app icon

- `icon/exifcleaner.ico`
- `icon/exifcleaner-icon-512.png`

## Browser tab and home screen

- `icon/favicon.svg`
- `icon/favicon-32.png`
- `icon/favicon-16.png`
- `icon/apple-touch-icon-180.png`

## GitHub social preview and avatars

- `social/exifcleaner-social-preview-1280x640.png`
- `social/exifcleaner-avatar-1024.png`

## DMG window: save as background.png and background + “@2x.png”

- `installer/dmg-background.png`
- `installer/dmg-background-2x.png`

## The graphic device (the removed line)

- `background/exifcleaner-removed-line-light.svg`
- `background/exifcleaner-removed-line-dark.svg`

## Sounds: raw WAVs for the app; MP3s mastered for speakers, for the web and posts

- `sound/exifcleaner-sweep.wav`
- `sound/exifcleaner-done.wav`
- `sound/exifcleaner-drop.wav`
- `sound/listening/exifcleaner-sweep.mp3`
- `sound/listening/exifcleaner-done.mp3`
- `sound/listening/exifcleaner-drop.mp3`

## The logo animation with its sound, for videos and talks

- `motion/exifcleaner-logo-animation.mp4`
- `motion/exifcleaner-logo-animation.webm`

## The photo grade (a LUT) and the example photos, with licenses

- `imagery/exifcleaner-daylight.cube`
- `imagery/README.md`

## Fonts for design apps (install) and the web

- `fonts/variable/`
- `fonts/static/`
- `fonts/web/`

## Colors, type and motion values for developers

- `../tokens.json`

## The whole brand as data, or as text for an AI assistant

- `../brand.json`
- `../BRAND.md`

## This book to print or send, a one-page summary, and a visual guide to every file

- `../exifcleaner-brand-book.pdf`
- `../exifcleaner-one-page.pdf`
- `index.html`

All logo SVGs are transparent, outlined (no fonts needed) and use the exact brand colors. `-light` files are colored for a light ground, `-dark` for a dark one. The macOS icon follows Apple's 1024 template (an 824 px body with a transparent margin); the full-bleed master is for tools that apply the shape themselves; `exifcleaner.ico` holds 16 to 256 px. The DMG backgrounds match electron-builder's default icon positions (130 and 410 on a 660 × 400 window); in the app's `build/` folder, name them `background.png` and, for the 2× file, `background` + `@2x.png`. Sounds: 48 kHz mono WAV, Sweep and Done at -20 LUFS, Drop at -34.5 LUFS (integrated, ITU-R BS.1770). Fonts: SIL Open Font License 1.1 (see `fonts/OFL-*.txt`); `variable/` holds every weight in one file, `static/` one file per named weight, `web/` Latin WOFF2 subsets with a `fonts.css`.
