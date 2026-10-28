# Muhammad Al-Muzahid — GitHub Pages

The root page at https://almuzahidseyam.github.io/ redirects to the public portfolio at https://almuzahidseyam.tech/ using an HTML refresh with a visible fallback link and canonical URL. Query strings and fragments are not forwarded.

Only the root index redirects. This is not a custom-domain or hostname-wide redirect: existing project paths, the 404 page and Gmail disclosures remain available. The private archive is separate at https://almuzahidseyam.web.app/ and is not linked or exposed by the redirect.

## Personal Gmail automation

The standalone `/gmail-cleanup/` overview and `/gmail-cleanup/privacy.html` describe **n8n Gmail Cleanup Personal** for the owner's Google OAuth configuration. They use no scripts and contain no mailbox records or credentials. Gmail processing runs locally, separately from this public documentation website. Update the disclosures whenever the actual data practices change.

## Publishing

GitHub Pages serves the `main` branch from the repository root. Keep `.nojekyll`, `index.html`, `404.html`, `robots.txt`, `sitemap.xml`, `site.webmanifest` and the `assets/` directory together. Do not add a CNAME: the public custom domain is hosted separately on Firebase.
