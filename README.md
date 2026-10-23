# Thejus Digital Card

A mobile-first, dark cyber-style digital contact card for Thejus T.K.

## Included
- Responsive cinematic mountain background and neon accents
- Downloadable vCard (`thejus-tk.vcf`)
- LinkedIn, Instagram, WhatsApp, email and portfolio links
- Native share menu / copy-link fallback
- On-demand QR code that encodes the deployed page URL
- Personal interests section
- No analytics or advertising cookies enabled by default

## Publish with GitHub Pages
1. Create a **separate public repository** named `thejus-digital-card`.
2. Upload `index.html`, `favicon.svg`, `thejus-tk.vcf`, and this README to the repository root.
3. Open **Settings → Pages**.
4. Under Build and deployment, select **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
5. Wait for GitHub Pages to publish the site. The URL should be `https://thejustk-byte.github.io/thejus-digital-card/`.
6. Open the published URL on a phone and test the contact download, social links, share button and QR code.

The QR is generated at runtime and encodes the current page URL, so it becomes useful after publication. You can then open “Show my QR” and save a screenshot or use a QR generator with the permanent URL for a print-ready version.

## Privacy-conscious analytics
Analytics is intentionally **not enabled**. If you want aggregate visit counts later, create a GoatCounter site and add its documented tracking snippet to `index.html`. Review its privacy settings and public counter options before enabling it. Do not put secrets, private tokens, or API keys in this static repository.

## Updating details
Edit `thejus-tk.vcf` and the links in `index.html`. Because this is a static site, changes are committed directly to GitHub and then redeployed by Pages.

## Important
The contact card is public. The phone number and email are deliberately included because they were provided for this purpose. Remove them from both `index.html` and the vCard if you later decide not to publish them.
