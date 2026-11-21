# Santa Fe Precision

Private study notes for Dennis Dawson, *Santa Fe Precision* (Master Point Press, 2019, ISBN 978-1-77140-209-5).

## Layout

The repository holds only `README.md`, `david-notes.md`, `ritz-notes.md`, and `david-notes.pdf` (a PDF of `david-notes.md`). The scanned book, its OCR, and the page images below are working material on the owner's disk: they are deliberately not committed, for copyright reasons. The `*n*` page references in the notes point at book pages, identified as follows.

```
santa-fe-precision.pdf   scanned book (107 two-page spreads, image only) — not committed
david-notes.md           short system outline (openings, responses, competition)
ritz-notes.md            fuller partner notes
ritz-notes.pdf           original partner notes (real text; searchable) — not committed
book/                    — not committed
  contents.md            section list taken from the contents pages
  santa-fe-precision.md  OCR of the whole book, one heading per page
  img/                   one grayscale PNG per book page (0001.png–0214.png)
```

## Finding a page

The scan starts at book page 2 (the copyright page). Each spread is two book pages: the left page of spread N is book page 2N, and the right page is 2N+1. Scan 21L is book page 42.

`book/img/0001.png` is book page 2, and `book/img/0214.png` is book page 215. The image number is the book page minus one, so book page 42 is `book/img/0041.png`. The same heading in `book/santa-fe-precision.md` is `## Scan 21L — book page 42`.

`book/contents.md` is the shortest way to find a section. The page numbers there are book pages.

## How to use the OCR

`book/santa-fe-precision.md` is good for finding a section and reading the explanation. It is not safe to copy a bid from. Hands and auctions that sit side by side were often read as one line, and a missed suit pip can remain a wrong digit (for example `2♥ or28` where the book has `2♥ or 2♠`). A void printed as dashes has no pip, so it stays as dashes. Faint pages are rough.

When a hand or auction matters, open the matching file in `book/img/`, or the original PDF.
