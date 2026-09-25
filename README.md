# Bluehance 360 - Daily Tech Digest (page host)

Static host for the daily tech digest, served by GitHub Pages.

| Address | What it is |
|---|---|
| [`/`](https://jagruti1223.github.io/bluehance-tech-digest-page/) | The newest day. A copy, so a bookmark of the bare URL keeps working |
| `/2026-09-25/` | That day, permanently. This is the address posted to ClickUp |
| [`/archive/`](https://jagruti1223.github.io/bluehance-tech-digest-page/archive/) | Every day published so far, newest first |

Each weekday gets its own dated address, so the link in the channel changes
daily and a link shared last week still shows what it showed when it was sent.
Days are never overwritten or removed.

Everything here is generated and pushed automatically each weekday at roughly
10:30 AM IST by the digest pipeline in the private `bluehance360-ops-briefing`
repository. **Do not edit these files by hand** - the next run overwrites the
root page and the archive.

The archive index is rebuilt from whatever dated directories exist, so a day
restored by hand reappears in it with no further bookkeeping.

## Why this repository is public

GitHub Pages cannot serve a private repository without a paid plan, so the page
- and only the page - lives in a public one. The content is aggregated public
tech news, published with `noindex, nofollow` so it stays out of search results.
Treat it as readable by anyone with the URL and never put anything internal here.

## Spotting a failed run

Every page carries its own date in the title. If the newest entry in the archive
is not the last working day, publishing failed rather than the news being quiet -
check the Actions tab of the private repository.

The 22 September page holds only 4 items because the digest ran twice that day;
the second run found just a few hours of new material. It is kept as it was.
