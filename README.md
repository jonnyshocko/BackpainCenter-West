# Back Pain Center Wentzville

Website for Back Pain Center Wentzville — chiropractic care and rehabilitation.

**Live:** [backpaincenterwentzville.com](https://www.backpaincenterwentzville.com)

## Setup

This is a single-page static site deployed via GitHub Pages.

### Form Backend (TODO)
The appointment request form currently logs to console. To wire it up:
1. Replace the `handleSubmit()` function's TODO comment with your API endpoint
2. Options: Formspree, Netlify Forms, custom backend, or email integration

### Custom Domain
1. In repo Settings → Pages → Custom domain, enter: `www.backpaincenterwentzville.com`
2. Update DNS at your registrar:
   - CNAME record: `www` → `<username>.github.io`
   - A records for apex domain:
     - `185.199.108.153`
     - `185.199.109.153`
     - `185.199.110.153`
     - `185.199.111.153`
3. Enable "Enforce HTTPS" in GitHub Pages settings

## Tech
- Pure HTML/CSS/JS (no build step)
- Google Fonts: Fraunces + DM Sans
- Fully responsive
- Scroll-triggered animations
- Auto-highlights today's hours
