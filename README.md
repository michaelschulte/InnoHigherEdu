# Innovating Higher Education &amp; Research for Generation Alpha

Homepage for the interdisciplinary **Community of Practice (CoP)** at the University of Bern,
exploring the digital transformation of higher education and research for Generation Alpha.
Funded by the Digitalisierungskommission (DigiK) of the University of Bern.

🌐 **Live site:** https://michaelschulte.github.io/InnoHigherEdu/

## About

A static site (plain HTML + CSS, no build step) served via GitHub Pages.

```
index.html        # the page
styles.css        # all styling
assets/team/      # team portraits (sourced from official UniBE profiles)
.nojekyll         # serve files as-is, skip Jekyll processing
```

## Editing

- **Content:** edit `index.html` directly.
- **Look & feel:** edit `styles.css` (colors live in the `:root` block at the top).
- **Team:** each person is a `<a class="member">` card in the `#team` section, linking to their
  official UniBE profile. To swap a photo, replace the file in `assets/team/`.

Changes pushed to the default branch publish automatically.
