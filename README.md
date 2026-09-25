# VETR project page

**Recursive Self-Improvement of Executable World Representation for Symbolic Graphics Reasoning**

Anonymous authors · ICLR 2027 submission

Static project page based on the existing Academic Project Page Template / Bulma layout. Open `index.html` or serve this directory with `python3 -m http.server 8000`.

## Content source

The title, abstract, and experimental results follow **`paper_source/evotrace_iclr2027.pdf`**, which differs from the adjacent LaTeX source. Per the requested figure selection, the images use the standalone PDFs below rather than the compiled manuscript figures.

- Figure 1: `paper_source/fig/figure1/VETR_figure1.pdf`.
- Figure 2: `paper_source/fig/figure2/vetr_figure2.pdf` (not the `_old` variant).
- BlenderGym matched image quality: Table 2, page 7.
- BlenderBench main results: Table 3, page 7.
- Execution-refiner ablation: selected columns of Table 4, page 8.
- BlenderPreserve diagnostic results: Section 4.5, page 9.

Figure assets are rendered from the specified standalone PDFs at 2200px width and stored in `static/images/vetr/` as WebP. Original PDFs are copied to `static/pdfs/vetr/figure1.pdf` and `static/pdfs/vetr/figure2.pdf`; clicking either image opens its original PDF.

## Resource links

PDF, arXiv, and GitHub are visibly disabled placeholders in `index.html`. To activate an entry, replace its `<button disabled ...>` with an `<a href="ACTUAL_URL" ...>` retaining the Bulma button classes, remove the `Soon` badge and placeholder class, and update its accessible label. No publication URL is assumed.

## Deployment

The GitHub Pages workflow stages only the page and referenced static assets in `_site/`. Source manuscripts, old template media, and README are not included in the published artifact. Pushes to `main` or `master` trigger deployment when Pages is configured for GitHub Actions.

## Credits

Built on the [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template), adapted from [Nerfies](https://nerfies.github.io/). Website template licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
