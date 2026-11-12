# QUASY series page

Source of https://quansyntax.github.io/quasy/, the landing page of the QUASY
(International Workshop on Quantitative Syntax) series.

- Plain static HTML (`index.html`) and one stylesheet (`style.css`); no build step.
  GitHub Pages publishes the `main` branch as is.
- Colours are CSS variables at the top of `style.css`.
- To add a new edition, copy one `<article class="conference">` block in
  `index.html`, put it at the top of the Workshops list, and add the proceedings
  link once the volume is in the ACL Anthology.
- `images/logonew.png` is the web-sized logo (700 px wide). `images/logonew.svg`
  uses live text and depends on locally installed fonts, so it is not used on the page.
