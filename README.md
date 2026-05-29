# Little Brush Games — Legal

Static legal-document website for Little Brush Games, intended for GitHub Pages.

## Pages

- `index.html` — legal document landing page
- `terms.html` — Terms & Conditions
- `privacy.html` — Privacy Policy
- `imprint.html` — Imprint / Impressum
- `styles.css` — shared styles

## Before publication

Replace all visible `TODO` fields with final legal information:

- legal name / company name or natural person name
- postal address required for Impressum
- contact email
- VAT ID, if applicable
- responsible person under German media law, if applicable
- exact list of analytics, crash reporting, ads, payments, hosting, and platform SDKs
- exact product names, purchase/subscription/refund rules, and jurisdiction choices

This repository contains a practical template and is not legal advice.

## GitHub Pages setup

1. Open repository **Settings → Pages**.
2. Source: **Deploy from a branch**.
3. Branch: `main`.
4. Folder: `/root`.
5. Save.

## Custom domain

After DNS is configured, add a file named `CNAME` with only the domain name, for example:

```text
legal.example.com
```

Recommended Cloudflare DNS for a subdomain:

```text
Type: CNAME
Name: legal
Target: littlebrushgames.github.io
Proxy status: DNS only during GitHub Pages certificate setup
```

After GitHub Pages provisions HTTPS successfully, Cloudflare proxy can be reviewed if needed.
