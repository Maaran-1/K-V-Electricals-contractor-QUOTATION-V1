# K V Electricals Quotation Desk — Standalone Edition

This project is based on the supplied source ZIP, modified to run without AppDeploy or any hosted backend.

## Requirements
- Node.js 20+ recommended
- npm
- Internet for the first `npm install`; Tesseract.js may download its OCR language data on first use.

## Run locally
1. Extract this ZIP.
2. Open a terminal in the extracted folder.
3. Run `npm install`
4. Run `npm run dev`
5. Open the local URL shown by Vite (usually http://localhost:5173).

## Build
- `npm run build`
- `npm run preview`

## Included
- Responsive React/Vite UI
- Local quotation saving in browser localStorage
- Create/edit/duplicate/delete quotation drafts
- Basic rough-text parser (not generative AI)
- Browser-side OCR using Tesseract.js; handwriting accuracy varies
- GST modes and live totals
- Print-to-PDF via browser print dialog
- JSON backup export/import

## Important limitations
- No AppDeploy SDK, hosted API, cloud sync, login, or multi-user permissions.
- Quotations are stored only in the current browser profile/device. Clearing browser data can erase them. Export backups regularly.
- Rough text extraction is a simple pattern-based parser, not AI; review every result.
- OCR requires the Tesseract language model download on first use and works best with printed text. Handwriting may be inaccurate.
- PDF export uses the browser's Print → Save as PDF. The quote layout is a starter layout and should be compared with the company's original PDF before production.
- Company details are prefilled from the supplied context; verify before using commercially.


## Mobile and quotation options update
- Responsive phone layout with larger touch targets, stacked form fields, and clearer source tabs.
- GST treatment includes **Excluding GST (GST extra)**, GST included, and No GST shown.
- New quotations start with editable payment/scope terms, including stage-based balance payment, extra-work charges, and civil/welding/fabrication/core-cutting/trenching/structural exclusions.
- Authorized signature area can be included or hidden from the PDF using the checkbox in Pricing & terms. The two thank-you messages remain; only signature blocks toggle.
- The decorative KV/CONTRACTOR placeholder box has been removed.
