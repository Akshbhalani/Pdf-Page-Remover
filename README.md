# PDF Page Remover

A free, browser-based tool for removing pages from PDF files. Choose pages to delete, confirm the selection, and download the updated PDF.

## Features

- Drag and drop a PDF or choose one from your device.
- Preview pages and select one or more pages for removal.
- Download the remaining pages as a new PDF.
- Files are processed in your browser and are not uploaded or saved by the site.
- No sign-up or build step required.

## Run locally

Keep `index.html`, `pdf.min.js`, `pdf-lib.min.js`, and `pdf.worker.min.js` together. From this folder, start a local static web server, for example:

```sh
python -m http.server 8000
```

Then open <http://localhost:8000> in your browser.

## Use

1. Upload a PDF by dropping it onto the page or choosing a file.
2. Select the pages you want to remove. Use **Select all** or **Clear selection** as needed.
3. Click **Delete** and confirm.
4. Click **Download PDF** to save the result.

Password-protected or damaged PDFs may not open.
