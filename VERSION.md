# LittleLink Extended Version History

## Current Version: v3.2.0

### v3.2.0 - 07/28/2026
Brings LittleLink Extended in line with the core LittleLink v3.11.0 conventions.

- Accessibility & markup: removed `role="button"` from link buttons, converted the button stack to `<nav aria-label="Links">`, wrapped page content in `<main>`, removed `tabindex` from static text, fixed the canonical tag (was an invalid `<meta>`), removed the obsolete keywords meta, made the favicon path relative, and added `theme-color` metas plus a fill-in Open Graph/Twitter block.
- Performance: preload hints for the three above-the-fold font weights, explicit dimensions and `fetchpriority` on the avatar, and placeholder avatars re-exported at true 128px/256px.
- CSS: synced `style.css` with core LittleLink (deduplicated legacy typography block, `theme-light` implementation, woff2-only `@font-face`) and deleted the legacy .eot/.svg/.ttf/.woff font files (~1.2 MB).
- Icons: optimized the nine largest icons (OpenStreetMap 114 KB → 38 KB, Epic Games 24 KB → 9 KB, and others).
- Knocket: replaced the incorrect logo from PR #37 with the official mark and corrected the button colors to the brand's dark green/lime.
- `preview.html` cleanup: alphabetized Bandsintown/BeReal, Filmweb/Flashes, and SimpleX/Skoob; fixed a duplicated `aria-hidden`, a missing `aria-hidden` (Devpost), non-standard alt text (Nostr, Skoob, itch.io), a stray `<br>`, and an empty Revolut `href`; normalized the Knocket example URL to the standard `#` placeholder; dropped the footer comment's reference to the nonexistent `privacy.html`.

### v3.1.2 - 03/16/2025
- Adds Babylist to `preview.html`

### v3.1.1 - 03/16/2025
- Fixed an issue where the Sensitive Content Warning Module did not 
automatically update to `dark` theme when `theme-auto` was applied.

### v3.1.0 - 03/16/2025
- Added Babylist button
- Fixed SimpleX Chat Alt
- Added Sensitve Content Warning Module
  - Adds `JS` folder with `sensitive-content.js`
  - Adds a new `css` file for `sensitve-content.css`
  - Adds a new `generic-warning.svg`

### v3.0.0 - 11/13/2024
LittleLink Extended has been updated to reflect all modernizations of the core LittleLink repo.

#### Major Changes
- Complete rebuild of CSS architecture
  - Enhanced `brands-extended.css`

- HTML Modernization
  - Rebuilt `preview.html`

#### Brand Changes
- Added NGL to LittleLink Extended from LittleLink
- Added Redbubble to LittleLink Extended from LittleLink
- Added Revolut to LittleLink Extended from LittleLink
- Added Trakt to LittleLink Extended from LittleLink
- Added Uptapped to LittleLink Extended from LittleLink
- Added Upwork to LittleLink Extended from LittleLink

---
For the complete history of changes, please visit:
https://github.com/sethcottle/littlelink-extended/releases

To learn more about the general overhaul of LittleLink, please visit:
https://github.com/sethcottle/littlelink/releases
