# Truth or Mole — Legal

Static legal-document website for **Truth or Mole**, a mobile game by **Little Brush Games**.

Production domain:

```text
https://legal.littlebrushgames.com
```

## Pages

- `index.html` — legal document landing page
- `terms.html` — Terms & Conditions
- `privacy.html` — Privacy Policy
- `imprint.html` — Imprint / Impressum
- `data-deletion.html` — data deletion request information
- `robots.txt` and `sitemap.xml` — crawler metadata
- `styles.css` — shared styles
- `CNAME` — GitHub Pages custom domain

## Current assumptions

- Product: Truth or Mole
- Operator: Little Brush Games
- Contact: support@littlebrushgames.com
- Jurisdiction: Germany
- Distribution: Apple App Store and Google Play
- Monetisation: subscriptions / in-app purchases
- Accounts/login: no Little Brush Games account required
- User-generated content: none through Little Brush Games services
- Analytics: anonymous, aggregated, or pseudonymous analytics depending on final SDK behaviour

## Still required before public launch

German/EU imprint details should be completed with final legally accurate data:

- full postal address
- responsible person details, if required
- VAT ID, if applicable
- final list of analytics / crash-reporting / subscription SDKs actually integrated in the app

This repository contains a practical template and is not legal advice.

## GitHub Pages setup

1. Open repository **Settings → Pages**.
2. Source: **Deploy from a branch**.
3. Branch: `main`.
4. Folder: `/root`.
5. Save.

## Cloudflare DNS

Recommended DNS record:

```text
Type: CNAME
Name: legal
Target: littlebrushgames.github.io
Proxy status: DNS only during GitHub Pages certificate setup
```

After GitHub Pages provisions HTTPS successfully, Cloudflare proxy can be reviewed if needed.
