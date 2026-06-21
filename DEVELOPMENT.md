# Richard Jason Simmons — Portfolio

Personal portfolio site for a Salesforce Administrator & Developer. A single self-contained
`index.html` (vanilla HTML/CSS/JS, no build step), hosted free on **GitHub Pages**.

## Editing content

All copy lives in three arrays near the bottom of `index.html`:

- `SKILLS` — toolkit cards
- `CERTS` — certifications
- `ROLES` — experience; drives both the list cards and the per-role detail pages

Edit the text there, not the markup.

## Adding gallery images

1. Drop the image in `images/`.
2. In the relevant `ROLES` entry, change a gallery item from `{ cap:"..." }` to
   `{ src:"images/your-file.png", cap:"Short caption" }`.

## Certification badges

Cards in the `CERTS` array use real badge images from `images/certs/` when present,
and fall back to the generic blue check badge if a file is missing. Save each badge
with the exact filename listed in `images/certs/.gitkeep`.

## Résumé versioning

All résumé versions live in `resumes/` (see `resumes/README.md` for the naming
convention). The site links to the root `resume.pdf`, which is a copy of the current
version — so the public URL never changes. To publish a new one: add it to `resumes/`,
copy it over `resume.pdf`, commit, and push.

## Open TODOs

- `--bc-green` — swap for Better Collective's exact brand-green hex.
- Add the 8 certification badge PNGs to `images/certs/`.
- Add Better Collective gallery screenshots to `images/` and reference them in the `ROLES` array.

Done: LinkedIn / Trailblazer / ResearchGate links, hosted `resume.pdf`, résumé archive,
and certification-badge image support.

## Local preview

Just open `index.html` in a browser, or run a static server from this folder:

```
python -m http.server 8000
```

Then visit http://localhost:8000.
