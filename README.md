# Sidqly Landing Website

This repository contains the public landing website for Sidqly.

## Brand

Sidqly is a donation transparency platform for mosques, Islamic charities, NGOs, and donors.

Sidqly helps donation teams manage donations, payment proof, approvals, Qurbani, Zakat, Sadaqah, Ramadan campaigns, reports, and donor trust from one place.

## Website

https://sidqly.com

## Contact

sidqly.team@gmail.com

## Repository purpose

This repository is for the public Sidqly landing page only.

It should not include:

- private app code
- Firebase service account keys
- real donor data
- real recipient data
- admin dashboard code
- Firestore rules for the actual app
- payment credentials
- production secrets

## Files

- `index.html` - main landing page
- `style.css` - landing page styles
- `robots.txt` - crawler access file
- `sitemap.xml` - sitemap for search engines
- `llms.txt` - AI-readable brand and site guide
- `about.txt` - plain text brand information

## Deployment

This website is intended to be deployed to Firebase Hosting.

Recommended command:

```bash
firebase deploy --only hosting
