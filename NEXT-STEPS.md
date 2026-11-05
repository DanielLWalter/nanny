# Next steps

Single-page bilingual (EN/ES) job posting: `index.html`, served by GitHub Pages from `main`.

- Language: `#en` / `#es` in the URL, otherwise follows the browser language.
- QR codes in `qr/` point to the site's root URL. Regenerate them only if the URL changes.
- The page has `noindex` set, so it is shared by QR code or link rather than through search.
- Take the page down once the position is filled, since it lists personal contact details.

## Flyer

The printable flyer is gitignored as print media. It lives in
`Code Assets/nanny/flyer` (`flyer.html` plus color and black-and-white PDFs, each half-letter and 2-up).
Restore it into `flyer/` to edit. Re-export with Chrome's print-to-PDF using `flyer.html`, `#2up`, `#bw` or `#bw-2up`.
