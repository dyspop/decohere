# Decohere
Promote human flourishing. Let's figure out how!


## Revisions

Every published version of the page is kept under `revision/<major>/<minor>/<patch>/`, and `/revision/` lists them with their notes. `index.html` is always a copy of the latest revision.

To publish a new revision:

1. Edit `index.html` and bump the version in its `.version` badge.
2. Copy `index.html` to `revision/<major>/<minor>/<patch>/index.html`.
3. Add an entry at the top of the list in `revision/index.html` with its `data-version`, date, and notes, and move the "(latest)" marker to it.

Addresses that don't match an exact revision, like `/revision/1` or `/revision/2/0/9`, are handled by `404.html`, which redirects to the newest listed revision at or below the one requested.
