# Bluehance 360 - Daily Tech Digest (page host)

This repository exists to serve one file: `index.html`, the daily tech digest
page, published through GitHub Pages at

**https://jagruti1223.github.io/bluehance-tech-digest-page/**

It is generated and pushed automatically every weekday by the digest pipeline
in the private `bluehance360-ops-briefing` repository. **Do not edit
`index.html` by hand** - the next run overwrites it.

The repository is public because GitHub Pages cannot serve a private repository
without a paid plan. The content is aggregated public tech news, but it carries
the company name, so the page is served with `noindex, nofollow` to keep it out
of search results. The link is for the team, not for the web.

Nothing here is a source of truth. The pipeline lives in `digest/` in the
private repository.

## When it updates

Every weekday at roughly 10:30 AM IST. `index.html` carries its own date in
the page title, so if that date is not today's, the pipeline failed rather
than the news being quiet - check the Actions tab of the private repository.
