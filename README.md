# DeepFlow — marketing website

Static site (no build step) for the DeepFlow Android app: Home, What's New, Privacy Policy, Terms of Service.

- Preview: `python -m http.server 8080` then open http://localhost:8080
- Theme tokens live in `:root` in `styles.css` (royal purple from the app icon + periwinkle accent).
- Swap the Play URL (`com.deepflow.app`) once the listing is live; screenshots are `assets/app-1..6.jpg`.
- New release: copy the `<article class="release">` block at the top of the timeline in `whats-new.html`.
- Deploy: GitHub Pages from `main` / root (`.nojekyll` included).
