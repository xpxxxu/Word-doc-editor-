# PhoneWordEditor

Mobile-first open-source editor based on Tiptap + Mammoth + html-to-docx.

## Features
- Import `.docx` (via Mammoth), `.html`, `.txt`
- Rich editing: headings, lists, tables, images, links
- Export to `.html` and `.docx` (client-side)
- Mobile-optimized UI

## Quick start
1. Install dependencies:

```bash
npm install
```

2. Run dev server:

```bash
npm run dev
```

3. Build for production:

```bash
npm run build
```

4. Deploy `dist/` to GitHub Pages or any static host.

## Notes & limitations
- DOCX import/export is functional for typical documents but may lose fidelity for complex Word features (advanced styles, tracked changes, headers/footers).
- If you need enterprise-grade Word round-trip fidelity, consider a commercial converter or server-side tool.

## License
MIT
