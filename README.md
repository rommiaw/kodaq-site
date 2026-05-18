# kodaq-site

Public site for the **KODAQ** iOS app, published by **Live Haven LLC**.

`index.html` is KODAQ's Privacy Policy + Support page. It is the URL
registered in App Store Connect for **both** the Privacy Policy URL and
the Support URL.

This repo is intentionally separate from the (private) KODAQ app source —
it contains only the public page, so hosting it via GitHub Pages exposes
nothing else.

## Hosting

GitHub Pages, served from the `main` branch root. To update the page
(e.g. change the contact email or policy text): edit `index.html`,
commit, push — Pages redeploys automatically. **Do not rename the repo
or move `index.html`**, or the URL registered in App Store Connect will
break.
