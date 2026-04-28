# TrailWeight — Landing Page

Static landing page for the TrailWeight backpacking trip planner apps.

**Live site:** https://sbrines.github.io/TrailWeight-Web *(after GitHub Pages is enabled)*

---

## Stack

- Vanilla HTML + CSS (no build step, no dependencies)
- Google Fonts (Inter)
- GitHub Pages for hosting

## Local preview

```bash
# Any static server works — e.g.:
npx serve .
# or
python3 -m http.server 8080
```

## Deploying

Push to `main` → GitHub Actions deploys automatically to GitHub Pages.

**One-time setup:**
1. Go to repo **Settings → Pages**
2. Set Source to **GitHub Actions**
3. The next push to `main` will deploy

> **Note:** The `.github/workflows/deploy.yml` file requires the `workflow` OAuth scope to push. Run `gh auth refresh -h github.com -s workflow` if needed.

---

## What to update before launch

- [ ] Replace `href="#"` on App Store and Google Play buttons with real store links
- [ ] Add real app screenshots to the hero section (replace phone mockup with actual screenshots)
- [ ] Add `og:image` meta tag with a social share preview image
- [ ] Update the `og:url` to the real domain if you set one up (e.g. `trailweight.app`)

---

## Related Repos

- **iOS + macOS**: [TrailWeight-iOS](https://github.com/sbrines/TrailWeight-iOS)
- **Android**: [TrailWeight-Android](https://github.com/sbrines/TrailWeight-Android)
