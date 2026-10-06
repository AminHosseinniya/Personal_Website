pdf.js 6.4.299 (pdfjs-dist, legacy build) - https://github.com/mozilla/pdf.js
Used by cv.html to render the CV. Licensed under Apache-2.0, see LICENSE.txt.
The legacy build is used because the modern build needs very recent JavaScript
features that many current browsers lack. The .mjs files are renamed to .js so
every host serves them with a JavaScript MIME type.
