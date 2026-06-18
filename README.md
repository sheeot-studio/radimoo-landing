# radimoo Landing Page

Static pre-launch landing page for collecting early waitlist signups.

## Files

- `index.html` - landing page markup
- `styles.css` - responsive styling
- `script.js` - small behavior layer and Tally link configuration

## Configure Tally

The waitlist is currently configured to use:

```text
https://tally.so/r/jagbXJ
```

## Recommended Tally Fields

- Email address
- English level
- Main goal
- Biggest speaking problem
- Interested in beta access?
- Optional note

## GitHub Pages

Recommended setup:

1. Create a dedicated public GitHub repository for this landing page.
2. Push the contents of this directory to the repository root.
3. In GitHub, go to `Settings` -> `Pages`.
4. Set `Source` to `Deploy from a branch`.
5. Set branch to `main` and folder to `/ (root)`.
6. Save and wait for GitHub Pages to publish the site.

After the custom domain is ready, configure the domain in GitHub Pages and add the required DNS records at the domain registrar.

## Pre-Publish Checklist

- Replace `hello@example.com` in `index.html`.
- Confirm the waitlist button opens the real Tally form.
- Confirm the Google Sheet sync works from Tally.
- Confirm the custom domain points to GitHub Pages.

## Suggested Repository Names

- `radimoo`
- `radimoo-landing`
- `radimoo-site`

## Local Preview

Open `index.html` in a browser. No build step is required.
