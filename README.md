## My Quarto Manuscript Template

This is a template repo for generating a manuscript from Quarto that has been modified to include the 
[apa-quarto](https://wjschne.github.io/apaquarto/) and [quarto-preprint](https://github.com/mvuorre/quarto-preprint) extensions.

Please see the guide at <https://quarto.org/docs/manuscripts/authoring/rstudio.html> about cloning this repo, 
and <https://quarto.org/docs/manuscripts/publishing.html> regarding how to set up GitHub Pages publication.

Note that the quarto-preprint extension currently (as of 2025-01-15) has issues with GitHub Pages rendering. My use scenario is to generate a PDF with `preprint-typst` (from quarto-preprint) that
can be manually uploaded to OSF Preprints, then I use the standard PDF output rendering for GitHub Pages (and comment out the `preprint-typst` section in `_quarto.yml`).

One of the reasons for using quarto-preprint is that it includes corresponding author email address on the first page, which is not default in the standard PDF output.