# Alarm Syncr site

Public pages for Alarm Syncr by Kheloton LLC, served by GitHub Pages from the `main` branch root.

| Page | URL |
|---|---|
| Home | https://pranavmdesai.github.io/alarm-syncr-site/ |
| Privacy Policy | https://pranavmdesai.github.io/alarm-syncr-site/privacy/ |

The privacy policy URL is entered in Play Console and linked from inside the app, so keep the `privacy/` path stable.

## Editing the policy

1. Edit `privacy/index.html`.
2. Change the "Effective" date near the top.
3. If the change affects what the app collects or shares, update the Data safety form in Play Console before releasing that app version.

## Files

- `assets/site.css`: shared styles (dark and light themes, print styles).
- `assets/icon.svg`: the app icon, copied from `brand/icon.svg` in the app repo without its monochrome layer.
- `assets/manrope.woff2`: Manrope, subset to Latin and served from this site so pages load nothing from third parties. License: `assets/manrope-OFL.txt`.
- `.nojekyll`: serve files as-is, without Jekyll.
