# QUASY series page

Source of https://quansyntax.github.io/quasy/, the landing page of the QUASY
(International Workshop on Quantitative Syntax) series.

- Plain static HTML (`index.html`) and one stylesheet (`style.css`); no build step.
  GitHub Pages publishes the `main` branch as is.

## When a new workshop is announced

1. Update the "Next workshop" box at the top of `index.html`.
2. In the Workshops list, remove `class="upcoming"` from the previous edition,
   copy one `<li>` block to the top, and give the new one `class="upcoming"`.
3. Add the proceedings link once the volume is in the ACL Anthology.
4. Point the "full scope" link under Topics to the new call for papers.
5. Update `og:description` in the page head (used for link previews).

## Shared look for QUASY websites

The workshop sites do not have to look the same, but sharing a few basics
keeps the series recognisable. The quickest start for a new workshop site is
to copy https://github.com/quansyntax/quasy2027 and change the photo, dates
and text.

- **Logo**: the QUASY logo with the year, on a white or very light background
  (it was designed for white). Use a PNG export; the SVG uses live text and
  depends on locally installed fonts.
- **Colours**:
  - `#2f4c5c` logo slate
  - `#0795a6` logo teal, for lines, dots and other decoration
  - `#067a88` darker teal, for links and small text (passes WCAG AA on white)
  - `#1E3542` deep slate, for headings and the footer
- **Fonts** (Google Fonts): Jost for headings, which echoes the Futura of the
  logo subtitle; Source Sans 3 for body text.
- **Motif**: the dots and lines of the dependency tree in the logo, used
  sparingly (list bullets, a divider, the favicon in `images/favicon.svg`).

## Files

- `images/logonew.png`: web-sized logo (700 px wide).
- `images/logonew.svg`: source file; uses live text, not used on the page.
- `images/favicon.svg`, `favicon-32.png`, `apple-touch-icon.png`: site icons.
- `images/og-image.jpg`: 1200 × 630 image shown in link previews.
