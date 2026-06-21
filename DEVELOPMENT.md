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

## Open TODOs

- Add `resume.pdf` to the repo root (both the hero and footer "Résumé" links point to it).
- `--bc-green` — swap for Better Collective's exact brand-green hex.
- Add Better Collective gallery screenshots to `images/` and reference them in the `ROLES` array.

Done: LinkedIn, Trailblazer, and ResearchGate links are filled in (`index.html` + `README.md`).

## Local preview

Just open `index.html` in a browser, or run a static server from this folder:

```
python -m http.server 8000
```

Then visit http://localhost:8000.
