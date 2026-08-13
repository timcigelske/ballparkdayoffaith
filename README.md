# Day of Faith static site — Lambeau Leap of Faith update

This is a Netlify-ready static site package for Day of Faith / Lambeau Leap of Faith.

## Current content status

- The main promotion is now **Lambeau Leap of Faith** on Sunday, September 6, 2026, across from Lambeau Field.
- The copy uses the IP-safer public language: Wisconsin vs. Notre Dame, Faith • Football • Fellowship, and Mass | Tailgate | Watch Party.
- The tailgate section includes the PayPal hosted button for Lambeau Leap of Faith Tailgate checkout.
- The copy states that the price includes tailgate food and non-alcoholic beverages, Mass is free and open to all, and the football game ticket is not included.
- A watch-party interest form is included for those without game tickets, with an attendance-count field.
- Netlify Forms are used for watch-party interest and ambassador/group contacts.

## Publishing workflow

The GitHub repository is connected to the Netlify project `ballparkdayoffaith` using continuous deployment.

1. Make website edits through ChatGPT/Codex.
2. Commit the updated files to the GitHub `main` branch.
3. Netlify automatically builds and publishes the new commit.
4. Verify the production site at [ballparkdayoffaith.netlify.app](https://ballparkdayoffaith.netlify.app).

Keep GitHub connected to Netlify so changes retain version history and deploy automatically.

## Files to edit most often

- `index.html` — content, links, PayPal button and forms.
- `styles.css` — design system, colors, layout.
- `assets/` — optimized photos and logo assets.

## PayPal hosted button

The embedded button currently uses hosted button ID `M99WVWGQ2EU5L` and the PayPal Hosted Buttons SDK URL supplied in the uploaded PayPal instructions.


Update note: The hero/header now uses the selected stadium-only Lambeau Field photo option.

<!-- ChatGPT GitHub content-write access and Netlify continuous deployment verified on 2026-08-13. -->
