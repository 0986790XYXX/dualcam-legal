# DualCam Legal Pages

Static site hosting the legal documents for **DualCam**, an iOS app that records the front and back cameras simultaneously and merges them into a single video file.

This repository is completely separate from the DualCam app source code. It only contains the public Privacy Policy and Terms of Service pages, served via GitHub Pages.

## Contents

```
docs/
├── _config.yml     # Jekyll config (minima theme, site title)
├── index.html      # Landing page linking to both documents
├── privacy.html    # Privacy Policy
└── terms.html      # Terms of Service
```

The pages are self-contained HTML with inline CSS (light/dark aware, mobile-friendly), so they render correctly whether or not Jekyll/minima processes them.

## Enabling GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Set **Branch** to `main` and the folder to **`/docs`**, then **Save**.
5. Wait ~60 seconds, then open the published URLs.

## Published URLs

Replace `<username>` and `<repo>` with your GitHub account and repository name:

- Landing: `https://<username>.github.io/<repo>/`
- Privacy: `https://<username>.github.io/<repo>/privacy.html`
- Terms:   `https://<username>.github.io/<repo>/terms.html`

Use the **Privacy** URL in App Store Connect for the Privacy Policy field.

## Notes

- Contact email across all pages: **dosmallnw@gmail.com** (real, monitored — Apple reviewers may email it).
- Effective date placeholder: `Last updated: 2026-07-15` — update as needed.
- `terms.html` §8 (Governing Law) contains a placeholder jurisdiction marked with an HTML comment — confirm and set the correct governing-law region before final release.
