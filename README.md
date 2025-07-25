# LaTeX / TeX Projects:

A clean, reproducible setup for compiling **LaTeX articles** and **Beamer presentations** locally and via CI (GitHub Actions) or Overleaf or ShareLaTex GWDG.

<p align="center">
  <img figures="manifold.png" alt="Manifold illustration" width="60%">
  <br>
  <img figures="uni-goettingen-logo.jpg" alt="GAU Göttingen logo" width="40%">
</p>

---

## Repository layout


> Tip: If the repo grows, move graphics to `figures/` and bibliographies to `bib/`. Sources use **relative paths**, so re‑organising is straightforward.

---

## Requirements

- **TeX Live 2023+** (Linux/macOS) or **MiKTeX 22+** (Windows)
- Tools: **latexmk** (recommended), **biber** (if using `biblatex`)
- Common packages (usually preinstalled):  
  `booktabs, article, amsmath, amssymb, mathtools, pgfplots, cleverref, caption, microtype, adjustbox, array, inputenc, parskip, amsthm, amsfonts, graphicx, xcolor, hyperref, geometry, biblatex, beamer, tikz, paper`

Keep your TeX distribution updated:

```bash
# TeX Live
tlmgr update --self --all
# MiKTeX → open MiKTeX Console → Updates
