# Socratic Seminar Workshop 3: From Seminar to Essay

A standalone GitHub Pages writing workshop that helps students turn seminar research into a compare-and-contrast essay.

## Features
- Thesis builder and sentence starters
- Guided introduction
- Three scaffolded compare/contrast body paragraphs
- Topic sentence and transition support
- Evidence + explanation prompts
- Conclusion builder
- MLA source / Works Cited organizer
- Full essay assembly and revision checklist
- Autosave and progress tracking
- Offline `.docx` generation using bundled JSZip
- MLA-style Word formatting: 1-inch margins, Times New Roman 12 pt, double spacing, MLA heading/title, paragraph indents, last-name/page-number header, Works Cited page

## GitHub Pages
Upload all four files (`index.html`, `styles.css`, `script.js`, `jszip.min.js`) to the repository root. Then enable **Settings > Pages > Deploy from a branch > main / root**.

Student responses are saved locally in that browser/device. Students should verify all MLA citations and revise generated starting drafts before submitting.

## Importing seminar notes and moving computers
- Upload text-based PDF, DOCX, TXT, or MD notes; preview/edit imported text in the notes area. PDF text extraction uses PDF.js from a CDN, so an internet connection is needed for PDF imports. Scanned/handwritten PDFs are not OCR-supported.
- Select a passage and copy it into body paragraph 1 evidence. This does not automatically infer citations or categorize research.
- Download a Workshop Progress JSON file at any time and upload it on another computer to restore responses. The browser autosave remains device-specific.
- The MLA DOCX export now preserves a manually edited full essay rather than always overwriting it.

## Organized PDF progress export
Students can download a PDF snapshot of all activity sections in their original order, including incomplete fields. This uses jsPDF from a CDN (internet required). PDFs are for viewing/submitting; save the JSON progress file to resume editing on another computer.

## Works Cited improvements
Source fields automatically generate draft MLA Works Cited entries if the manual MLA entry is empty. A live preview shows entries, alphabetized. Word export places Works Cited on a separate page with hanging indents. Organized progress PDF also includes a Works Cited page. Students should verify MLA citation accuracy.
