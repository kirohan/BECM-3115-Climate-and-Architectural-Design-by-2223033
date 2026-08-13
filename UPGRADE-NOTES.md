# BECM 3115 Website Upgrade — Slidewise QB Edition

## Added

- New **Slidewise QB Analysis** navigation module.
- Two clearly separated groups: **Section A (11 lectures)** and **Section B (7 lecture reports)**.
- Section B **Lecture 03.0** and **03.1** remain independent.
- 18 individual question-to-slide mapping PDFs bundled inside the repository.
- One-click ZIP download containing all 18 mapping reports.
- Lecture cards showing slides reviewed, QB links, mapped marks and Exact/Direct/Partial distribution.
- Mobile-friendly full-text transcription for every slidewise analysis PDF.
- Slidewise report pages included in the global English/Bangla search index.

## Focus Mode 2.0

- Press `F` or use the visible **Focus** control.
- Standard sidebar, topbar and footer disappear.
- Centered distraction-free reading column.
- Floating Focus Dock with Search, Exit and `A− / A / A+` reading-size controls.
- `Esc` exits Focus Mode when search is closed.
- Reading size and Focus preference persist locally.

## UI / performance

- Refined modern card system and responsive lecture grid.
- Improved page hero treatments, hierarchy and motion.
- Reduced-motion preference remains respected.
- Service worker upgraded to v2 and avoids caching PDF range requests.
- Still static: no framework, CDN, npm install or build step required.

**Website credit:** Made by K.I.Rohan

## v3 - PDF-faithful Slidewise Reader

- Replaced the plain-text Slidewise QB report reader with page-faithful visual rendering.
- All 18 lecture reports are rendered page-by-page (147 pages total) from the original PDFs.
- Tables, typography, colours, spacing, callouts, sketches and page hierarchy now appear exactly as in the report PDFs.
- Added Fit Page and Detail/Zoom modes plus per-page fullscreen viewing.
- Added responsive mobile handling: fit-to-screen by default, horizontal detail mode when larger text is needed.
- Kept the text transcription behind a collapsed accessibility/search section instead of using it as the primary reading UI.
- Focus Mode now widens report reading space and retains report zoom controls.
- Deep links from search results still jump to the matching report page.
- Service-worker cache bumped to v3 so deployed GitHub Pages clients do not keep the older plain-text reader.
