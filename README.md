# elizachat-site-mockup

Static mockup of the ElizaChat landing page ("The Eliza Story"), exported from the
ElizaChat Brand System design canvas.

`index.html` is the export, unmodified. It is fully self-contained — fonts and assets
are bundled into the file and unpacked by its own script on load, so there is nothing
to build and no dependencies to install.

The embedded Google Fonts licence comment at the top of `index.html` must stay in place.

## Local preview

    python3 -m http.server 8000

Then open http://localhost:8000

## Deploy

Static site, no build step. Output directory is the repo root.
