# PDF.js / ng2-pdf-viewer

This repository is a customized fersion of Mozilla's PDF.js, intended for fixing `Cannot read property 'div' of undefined` issue on ng2-pdf-viewer.

See https://github.com/mozilla/pdf.js for info regarding PDF.js.
See https://github.com/VadimDez/ng2-pdf-viewer for info regarding ng2-pdf-viewer.

The issue this repo fixes is dicussed (here[https://github.com/VadimDez/ng2-pdf-viewer/issues/367]).

# Installation

This would override the pdf.js dependency on ng2-pdf-viewer.
Install with `npm install @noamyg/pdfjs-dist --save`.