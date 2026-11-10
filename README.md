# mohamed-abdelsattar92.github.io

Personal site of **Mohamed Abdel Sattar**: mentor, career coach and Tech Lead.
Live at <https://mohamed-abdelsattar92.github.io/>.

## Structure

Plain HTML and CSS with no build step. GitHub Pages serves the files as-is, and `.nojekyll` turns off Jekyll processing.

```
index.html            page content (all copy lives here)
assets/css/style.css  styles: light/dark tokens at the top, bento grid, breakpoints
assets/img/           headshot (jpg + webp), share image, apple-touch icon
favicon.svg
```

## Editing

- **Copy and stats:** edit `index.html`. The mentoring numbers are in the "Impact" block.
- **Colors:** change the CSS variables at the top of `style.css` (`--grad`, `--a1`, `--a2`, …).
- **Booking links:** ICCY (`iccy.app/en/coach/mohamed-abdelsattar`) and ADPList (`adplist.org/mentors/mohamed-abdel-sattar`).

## Preview locally

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.
