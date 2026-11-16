# Distribution notes

This is the compressed distribution copy of the skill. The full-size originals were about 383 MB.

- **Opaque pictures** (backgrounds and scenes, 50 files) are JPEG, quality 90, with the long edge capped at 1600 px. Their filenames now end in `.jpg`.
- **Transparent pictures** (cutouts, props and components, 90 files plus `preview.png`) stay PNG. Those larger than 1100 px on the long edge were resized to 1100 px, keeping their proportions and alpha.
- **Text regions** in the catalog are fractions of the whole picture, so they are unchanged and still line up.
- **`reference.pptx` and `layout-library.pptx`** have the same slides, text and layouts. Their embedded pictures were compressed the same way, and identical pictures are stored once. Slide text remains editable.
- **The catalog** records the new `path`, `width`, `height` and `sha256` of every picture, plus `originalWidth`, `originalHeight` and `originalSha256` for the full-size source.
- The `*-index.jpg` proof sheets and the prompt and manifest files are unchanged apart from updated filenames.
