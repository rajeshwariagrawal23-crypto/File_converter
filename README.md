# Convertly — Office Edition

Static website: HTML, CSS and JavaScript only. No backend or build step.

## Run / deploy
Keep `index.html`, `style.css`, and `app.js` together in the root of a GitHub repository. Open `index.html` in a browser or deploy the repository to Vercel (Framework: Other, no build command). On Vercel, use the repository root as the project root.

## Supported conversions
- JPG, PNG, WEBP, BMP, SVG to other supported images or PDF; multiple images to a single PDF
- PDF to TXT, basic DOCX, PNG/JPG (multipage images zipped)
- DOCX to TXT, HTML, text-based PDF
- XLSX, XLS, ODS to CSV (first sheet), JSON, HTML, TXT, text-based PDF or DOCX
- CSV to XLSX; TXT to XLSX or basic PPTX
- PPTX to TXT, text-based PDF or DOCX
- Text/HTML/Markdown to supported text/document outputs

## Limitations
PowerPoint slide visuals, chart formatting, PDF page layouts, and complex Excel/Word formatting are NOT reproduced in text-based conversions. Legacy PPT files are not supported. Scanned PDFs require OCR, not included. CSV exports only the first worksheet. Some formats are not mutually convertible. Libraries load from third-party CDNs, so an internet connection is required; no file is intentionally uploaded to a conversion server. Large documents may exhaust browser memory. For exact-fidelity Office/PDF conversion, use a backend with LibreOffice or a dedicated converter.

## Troubleshooting
If conversion reports a missing library, check network access and content blockers. Use your browser developer console for errors. Test with a simple DOCX, XLSX, and PPTX before uploading large files.
