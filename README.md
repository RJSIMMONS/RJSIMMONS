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

Search `index.html` for these placeholders and replace with real values:

- `RESUME_PDF_URL`, `LINKEDIN_URL`, `TRAILBLAZER_URL`
- ResearchGate publication link (`href="#"` in the Education block)
- `--bc-green` — Better Collective's exact brand-green hex

## Local preview

Just open `index.html` in a browser, or run a static server from this folder:

```
python -m http.server 8000
```

Then visit http://localhost:8000.
