# Portfolio

Personal portfolio site for Dayana Lorza.

## Snapshot

![Current portfolio snapshot](snapshot.png)

## Structure

- `index.html` — current portfolio site
- `css/`, `js/`, `images/`, `resume/` — current site assets
- `archive/` — previous portfolio versions
  - `2018/` — original developer portfolio
  - `2024/` — portfolio refresh

The small 🥚 beside the copyright on the current site links to the archive.

## Deployment and contact form

Netlify deploys the `master` branch from this repository. The site is static; no PHP server is needed. The contact form uses Netlify Forms with a honeypot field. Form submissions appear in the site's **Forms** dashboard after form detection processes the next deployment. Configure submission notifications in Netlify if email alerts are wanted.

The site can be opened directly in a browser for a visual preview. Form submissions work on the deployed Netlify site, not from a `file://` preview.

## Privacy

No direct email address, analytics ID, or macOS metadata is stored in the repository. Local metadata and temporary files are excluded through `.gitignore`.
