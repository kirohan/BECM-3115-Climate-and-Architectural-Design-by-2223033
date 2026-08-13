# BECM 3115 — Climate & Architectural Design

A fast, mobile-friendly, static study website prepared for GitHub Pages.

**Website credit:** Made by K.I.Rohan

## Included modules

- Homepage / complete website guide
- Part A Master Class Note
- Part B Master Class Note
- Topic-wise Question Bank Analysis (8-set distribution)
- Formula + Theory + Proof/Derivations
- Complete Question Bank Solution (2016–2024 regular papers)
- Dedicated Backlog / Retake Preparation
- Full PDF downloads
- Course-wide English + Bangla search
- Light/Dark themes
- Focus Mode (`F`)
- Keyboard Search (`/`)
- Mobile navigation
- Offline-friendly service worker
- No framework, no build step, no CDN dependency

## GitHub Pages deployment

1. Create a GitHub repository (recommended name: `BECM-3115-Climate-and-Architectural-Design-by-KI-Rohan`).
2. Upload **all files and folders from this repository package to the repository root**.
3. Commit to the `main` branch.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Choose branch `main` and folder `/ (root)`, then Save.
7. Your site will be available at `https://<username>.github.io/<repository-name>/`.

## Local preview

```bash
python -m http.server 8000
```

Then open `http://localhost:8000/`.

## Source discipline

The interactive site is based on the supplied/generated course PDFs. The full PDFs are bundled under `assets/pdfs/` and complete page-by-page searchable transcriptions are stored under `content/`. Repeated questions are prioritized according to the supplied question-bank analysis.

The Backlog Preparation page is a study strategy derived from the regular question-bank patterns. No separate backlog-specific paper was supplied, so the website does not present it as a separate statistical question-bank analysis.
