# Las Vegas Cosmetic Recovery — GitHub Pages Demo

Mobile-first static rebuild for **Las Vegas Cosmetic Recovery**, designed for client review and GitHub Pages.

## Expected demo URL

https://hustlescientist.github.io/LV-massage/

If Pages has not been enabled yet, set **Repository Settings → Pages → Source → GitHub Actions**.

## Included

- Responsive patient-focused homepage
- Sticky desktop navigation and mobile navigation
- Mobile Call / Text / Book action bar
- Founder biography and credentials
- Core recovery services
- Recovery phases
- Visual gallery using current client imagery
- Testimonial / Google review CTA
- 12 built-in recovery journal articles with filters and shareable `?article=` deep links
- Talk Plastic Surgery podcast feature
- YouTube education feature
- Cosmetic Surgery Therapist Training feature
- Three digital product cards
- Google, Facebook, Instagram, YouTube, and TikTok links
- GitHub Pages deployment workflow
- No framework or build step

## Media architecture

Current images are referenced from the existing Wix CDN through the centralized `MEDIA` map in `assets/app.js`. They can later be swapped to GitHub-hosted assets, GoHighLevel Media URLs, or another CDN without changing page markup.

## Production checklist

1. Confirm the exact Las Vegas street address / suite.
2. Export original-resolution media from Wix and replace resized CDN variants.
3. Connect appointment forms to the production CRM/calendar.
4. Review medical/outcome claims and legal policies for the final stack.
5. Replace outbound legacy Wix links as rebuilt pages come online.
