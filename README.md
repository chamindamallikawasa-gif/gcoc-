# CHAMINDA AMARASENA – Product Certificate Generator

Vercel-ready Next.js app for the supplied General Product Certificate of Conformity PDF.

## Run
```bash
npm install
npm run dev
```

Open http://localhost:3000

## Workflow
1. Download `CHAMINDA_PO_PDF_Template.xlsx` from the app.
2. Enter one product/PO per row.
3. Upload the Excel file.
4. Generate PDFs. One PDF is created for each PO row and downloaded as a ZIP.
5. Report history is saved in the browser's localStorage for this app/browser.

## Deploy to Vercel
Push this folder to GitHub and import it into Vercel. No server database is required for the included version.

> Note: Report history is browser-local. For shared multi-user report storage, connect Supabase/Vercel Postgres + Blob storage later.
