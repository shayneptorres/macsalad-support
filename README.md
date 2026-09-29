# MacSalad — Support

Public support site for the iOS app **MacSalad**, served via GitHub Pages.
This repo exists only to host these pages — the app source lives in a
separate private repo.

- `index.html` — support home: what the app is, features, how estimating
  works, contact, FAQ, and TestFlight feedback for beta testers. This is the
  **Support URL** on the App Store listing.
- `privacy.html` — privacy policy. This is the **Privacy Policy URL** on the
  App Store listing and in TestFlight's Test Information.

Both URLs must stay reachable. Apple checks them during review.

## Editing

Plain HTML plus `style.css` — no build step, no dependencies, no external
resources. Edit and push; GitHub Pages redeploys in about a minute.

When the app's data handling changes (for example, Claude estimates reaching
the App Store build), update `privacy.html` and its "Last updated" date.

## Setup

Settings → Pages → Source: **Deploy from a branch**, branch `main`, folder `/ (root)`.
