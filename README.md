# niftysphere-public

Public static site for Niftysphere legal pages (GitHub Pages).

**This repo is separate from the private `ZSH` monorepo.**

## Pages

| Page | File | URL (after Pages is on) |
|------|------|-------------------------|
| Home | `index.html` | https://mzeeeshan.github.io/niftysphere-public/ |
| Privacy | `privacy.html` | https://mzeeeshan.github.io/niftysphere-public/privacy.html |
| Terms | `terms.html` | https://mzeeeshan.github.io/niftysphere-public/terms.html |

## Local edit

Edit the HTML, commit, push to `main`. GitHub Pages serves from the `main` branch root.

## App / Play Console

Put these URLs in:

- Play Console → Privacy Policy
- `nifty_fe` → `lib/constant.dart` → `privacyPolicyUrl` / `termsOfServiceUrl`

Update the contact email in both HTML files before treating them as final.
