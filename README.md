# ICNP Learn the Surahs by Heart — Complete Standalone Web App

This package contains the complete Quran verse dataset used by the app (6,236 ayahs across 114 surahs) plus the ICNP web app. The app does not embed the original Adem Deniz page.

## Files
- `index.html` — application UI and learning modes.
- `data.json` — Arabic Quran text, English translation, transliteration, and verse metadata for all 114 surahs.

## GitHub Pages
Upload **both files to the repository root**, then enable Pages from the `main` branch and `/ (root)`.

## Audio
Verse audio is streamed from the Al Quran Cloud CDN using the documented `ar.alafasy` ayah URL pattern. The Quran text itself is bundled locally, so the app does not depend on the original game site. Audio therefore requires an internet connection.

## Content/source note
The Arabic and English text included here was extracted from the installed LaTeX `quran` package available in the build environment. The English translation in that package is the Pickthall translation. Verify the Quran text/translation against your preferred authoritative Mushaf before institutional deployment.
