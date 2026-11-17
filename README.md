# Quire PDF Editor

A free PDF editor that runs entirely in the browser. Files are never uploaded; everything happens on your own computer.

## Use it

Open `index.html` in Chrome, Edge or Firefox (an internet connection is needed the first time, to load the two PDF libraries), or host the repo with GitHub Pages.

## What it does

- Edit existing text: click a line to retype it
- Add text, highlights, freehand drawing, shapes, ticks, whiteout, images and signatures
- Fill in form fields
- Redact: blacked-out pages are saved as images so the hidden text is removed from the file
- Reorder, rotate, duplicate, delete and insert pages; merge in other PDFs or images
- Save the whole PDF, selected pages as a new PDF, or the current page as a PNG

## Limits

- Replacement text uses Helvetica, Times or Courier, so it may not match the original font
- Characters outside the standard Western set are saved as "?"
- Password-restricted PDFs open as page images (annotate, sign and rearrange only)
- No OCR, text search or password protection

## Built with

[pdf.js](https://mozilla.github.io/pdf.js/) for rendering and [pdf-lib](https://pdf-lib.js.org/) for writing, both loaded from cdnjs. The whole app is the single `index.html` file.
