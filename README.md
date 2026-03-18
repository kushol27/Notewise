# NoteWise – Local AI Text Analyzer

**NoteWise** is a lightweight, browser-based text analysis and summarization tool. It works entirely in the browser — no paid APIs required. Upload files or type text, and get instant overviews, highlights, key terms, and takeaways.

---

## Features

- Upload text files, PDFs, or images (JPG, PNG, GIF, WEBP).  
- OCR support for images using **Tesseract.js**.  
- Extracts text from PDFs using **PDF.js**.  
- Live character count for your text.  
- Simple local AI-style summarization:  
  - Overview  
  - Detailed summary  
  - Highlights  
  - Key terms  
  - Takeaways  
- Copy summary to clipboard or download as `.txt`.  
- Fully offline, works entirely in your browser.  
- UI remains clean and simple, no unnecessary changes.

---

## Usage

1. Open `index.html` in a modern browser (Chrome, Firefox, Edge).  
2. Upload a file or paste/type text in the textarea.  
3. Click **Analyze & Summarize**.  
4. View the results in the right panel.  
5. Optional: Use **Copy** or **Download** buttons to save the summary.  

---

## Supported File Types

- Text: `.txt`  
- PDF: `.pdf`  
- Images: `.jpg`, `.jpeg`, `.png`, `.gif`, `.webp`  

---

## Dependencies

- [Tesseract.js](https://github.com/naptha/tesseract.js) – OCR for images  
- [PDF.js](https://mozilla.github.io/pdf.js/) – PDF text extraction  

Both are loaded via CDN, so no installation required.

---

## Example Workflow

1. Upload an image of a document (`.png` or `.jpg`).  
2. Wait for OCR to extract the text.  
3. Click **Analyze & Summarize**.  
4. Read the generated overview, highlights, and key terms.  
5. Copy or download the summary.

---

## Notes

- Works offline after initial CDN load.  
- Local summarization is basic; it extracts key sentences and frequent words.  
- For large PDFs or images, processing may take a few seconds.

---

## License

MIT License © 2026  
Free to use, modify, and distribute.

---

## Screenshots

*(Optional: Add screenshots of the UI and analysis panel here)*

---

**Author:** @KHUSHOL – NoteWise Project
**Contributi** @dr34m14  – NoteWise Project 1.01
