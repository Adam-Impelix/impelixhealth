# impelix.health

Static site, no build step. Deploys directly on GitHub Pages (Settings → Pages → Deploy from branch → `main` / root).

## Before going live
1. **Contact.** Email only for now (no form). If a form is wanted later, GitHub Pages needs a service such as Formspree; the privacy notice would need updating.
2. **Quarterly update PDF.** Q3 2026 is in place at `updates/2026-Q3-Impelix-Update.pdf`. Add future issues to `updates.html`.
3. **Custom domain.** Add a `CNAME` file containing `impelix.health` and point DNS at GitHub Pages. Enable "Enforce HTTPS."
4. **Brand.** `img/impelix-lockup.png` is the header logo; `img/impelix-mark.png` is the drop mark used for favicon and touch icon. Palette in `css/style.css` is sampled from the lockup (#1C4689 / #2A5C9D / #4079B1).
5. **Counsel pass.** Footer disclaimer and the "Where we are" ledger should be read by Aaron (securities language) and Meryam (disclosure) before the site is indexed.

## Disclosure rules baked into the copy
- Method described only at the level of the published 2025 systematic review ("segmental ankle bioimpedance spectroscopy"). No electrode geometry, frequencies, signal processing, phantom, component platform, or prototype images.
- No "detects," "predicts," or outcome/cost-savings claims. Practice economics stated as a model.
- Device described as investigational, not for sale, in the footer of every page and in a callout on the approach page (Health Canada / FDA pre-licence advertising).
- No competitor named.
- Quarterly update list is opt-in by email request, with unsubscribe language (CASL).

## Structure
- `index.html` — mission, ledger of what's been built, go-to-market, CTA
- `problem.html` — problem statement and market funnel
- `approach.html` — platform, delivery model, regulatory path
- `evidence.html` — published work, planned study, timeline, reporting commitment
- `team.html`
- `updates.html` — quarterly one-pager archive
- `contact.html`, `privacy.html`
- `css/style.css` — single stylesheet; IBM Plex Sans/Serif via Google Fonts
