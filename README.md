# Coupling Ratio Explorer — Interactive Fig. S1

Interactive supplementary figure for:

> Güllü, H., Eriten, K. *Lateral–rotational coupling of monopile head stiffness under depth-dependent cyclic changes in soil stiffness.* Submitted to Computers and Geotechnics.

**Open in the browser:** https://kayahaneriten.github.io/coupling-ratio-explorer/

## What it shows
- How the depth profile of a cyclic stiffness change moves the coupling ratio ρ = −K_LR/√(K_L K_R) and the rotation point z_r of a monopile.
- Move the depth gradient β₁ to concentrate the softening near the surface (red) or at depth (blue), and press play to let the cycles run. For the semi-rigid pile, the total change and its depth-gradient term are shown separately.
- The bottom strip shows that stiffness histories with the same 1.2% drop in natural frequency change the mudline displacement and the coupling ratio by different amounts, while the mudline rotation hardly changes (cf. Fig. 15 of the article).

## Scope
The figure implements the Winkler models of Section 2 and Appendix B of the article (rigid pile; semi-rigid pile with Π = 63, α = 1; tower model of Appendix B.2 with Π = 63, n = 0.5, N = 10⁴). Marks on the slider refer to the scenarios of Table 1. It contains no finite element results or other data.

## Use
Single self-contained HTML file (`index.html`); no installation, no external requests. It also works offline when downloaded and opened in a web browser.

## License
Released under the MIT License (see `LICENSE`). If you use this figure, please cite the article above.
