# Medicus website

Support page and privacy policy for Medicus (iPhone, iPad, Mac), served with GitHub Pages at
https://colgate666.github.io/medicus-site/.

- Support: `index.html` (English), `es/index.html` (Spanish)
- Privacy policy: `privacy.html`, `es/privacy.html`
- `style.css` (light and dark), `logo.svg` (the app icon's background, Psi and serpent layers)

The app links to the privacy policy at these exact URLs (`PurchaseLinks` in `Medicus/App/Purchases/ProductIDs.swift`),
so keep the paths:

- https://colgate666.github.io/medicus-site/privacy.html
- https://colgate666.github.io/medicus-site/es/privacy.html

App Store Connect uses `/` and `/es/` as the Support URLs (`AppStore/Metadata.md`).

No trackers, external fonts or scripts. When the policy changes, update the effective date on both privacy pages.
