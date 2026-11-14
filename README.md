# Burner OS — legal & support pages

This repository hosts the legal and support pages for **Burner OS**, the offline narrative
detective game for iPhone.

| Page | File | Where it is used |
|---|---|---|
| Landing | `index.html` | General entry point |
| Privacy Policy | `privacy.html` | Paywall footer + **App Store Connect → Privacy Policy URL** |
| Terms of Use | `terms.html` | Paywall footer |
| EULA | `eula.html` | Licence reference |
| Support | `support.html` | Paywall footer + App Store Connect → Support URL |

## Live site

<https://mylove1596-bit.github.io/Burner-OS/>

## Editing

Edit the HTML files directly and push to `main` — GitHub Actions redeploys the site automatically.

The pages are plain HTML with one shared stylesheet (`style.css`). Keep the structure consistent
with the sibling `Crowned` repository.

## Before publishing

- [x] Contact address unified to `mylove1596@gamail.com` (support / legal / privacy all point to it).
- [x] "Last updated" date bumped on the pages that changed (→ 14 November 2026).
- [x] Copy matches the app's actual behaviour: Case #01 is free and unlimited, the other ten
      cases are locked, and the free tier allows 1 hint / 1 warrant / 3 PIN guesses per case.
- [ ] Replace the placeholder App Store link in `index.html` (`https://apps.apple.com/`) with the
      real listing URL once the app is approved.

## Contact

Published by an independent developer. Not affiliated with Apple, Inc.
