# rynklly.github.io

Personal academic site for Ryan Kelly, served by GitHub Pages at <https://rynklly.github.io>.

Plain HTML and CSS, no build step. Edit `index.html` for content and `style.css` for appearance; changes go live a minute or two after you push.

## Files

- `index.html` — the page (About, Projects, Experience, Skills, Contact)
- `style.css` — styling, with automatic dark mode
- `cv.pdf` — public CV (the phone number is left off; the application CV has it)
- `materials/` — teaching worksheets and keys (PDFs)
- `.nojekyll` — tells GitHub Pages to serve files as-is

## Adding a worksheet

1. Put the PDF(s) in `materials/`.
2. In `index.html`, find the `WORKSHEETS` comment in the worksheets card, uncomment the `<ul class="files">` list, and add one line per worksheet.
