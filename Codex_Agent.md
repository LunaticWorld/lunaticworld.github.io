# LunaticWorld GitHub Pages Codex Guide

## Latest Snapshot

- 2026-05-11 app icon pass: the root `index.html` is the public GitHub Pages landing page for LunaticWorld apps. The all-app list uses real Android launcher WebP assets from sibling `D:\android_ws` projects under `assets/app-icons/`, with decorative `<img>` tags sized through the shared `.app-icon` class. Keep app policy/store links in `index.html` and keep binary app icon assets small enough for GitHub Pages.

## Structure

- `index.html`: main public app and policy index page.
- `assets/app-icons/`: extracted app launcher icons used by `index.html`.
- App policy folders such as `braingame/`, `lockonword/`, `short_temprecipitationforecast/`, `stockdisclosure/`, and `stockdisclosureUS/`: policy/support documents linked from the index.
- `.well-known/`, `ads.txt`, `app-ads.txt`, `.nojekyll`: static hosting and app/store verification support files.

## History

- 2026-05-11: Added this guide while adding real app launcher icons to the app list.
