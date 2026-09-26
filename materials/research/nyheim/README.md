# Nyheim project figures and source notes

The website summarizes the supplied **Nyheim Plasma Institute** project archive.
Paths below are relative to that archive, not this repository.

## Figures

- `diffusion-exponent-map.png`: Figure 5 on PDF page 7 of
  `Descriptions/Project Description.pdf` (draft dated September 27, 2025).
  Rendered directly from the original PDF with PyMuPDF at 4x scale using the
  page rectangle `(159, 76, 445, 402)` in points. The crop retains both maps,
  axis labels, and the shared legend. No numerical values or labels were changed.
  The draft does not specify this figure's ensemble size or exact slope window.
- `elfin-spectral-fits.png`: unchanged copy of
  `Code/Python Code/Plots/Curve_Fit/fitted curve small R multiplot.png`.
  Six examples of normalized trapped-electron spectra and power-law fits with
  exponential cutoffs for precipitation-to-trapped-flux ratios below 0.1.
  The spectral amplitude A is distinct from the diffusion exponent A.

## Content evidence

- `materials/cv.pdf` in this website establishes the role, supervisor, institution,
  and 2025-2026 period.
- `Descriptions/Project Description.pdf`, pages 2-3 and 7, describes the stochastic
  mapping, early-time spreading, and dependence on initial conditions.
- `Descriptions/2024PoP_Mitia_Jacob_two_frequencies_.pdf` is a later working draft
  dated November 6, 2025. Both drafts contain unfinished sections; the page makes
  no publication or first-authorship claim. The proposed link between trapping
  probability and the spreading exponent is not presented as an established result.
- `Code/Model Proj/New V2.jl` implements root finding, separatrix-area quadrature,
  trapping/bunching updates, ensemble simulation, and transport diagnostics.
  Different code versions use different slope definitions, so the website does
  not state a universal fit window, ensemble size, or precise spreading metric.
- `Code/Python Code/new_lib.py`, `Perp Group plot and Medians.py`, and `KDE.py`
  support the flux-processing, coordinate-alignment, fitting, and group-comparison
  descriptions. `Reports/Data Project/Old/Project_1 (7).pdf`, physical pages 6,
  9, and 10, documents normalization, spectral fitting, and precipitation ratios.
- `Code/Julia Code/seeded multiinvariant.jl` and
  `Reports/Math Project/Math Project (11).pdf` support the Hamiltonian-system
  and adiabatic-invariant summary.

The manuscript drafts, raw satellite data, and source archive have not been
copied into the website. The figures describe numerical and observational
analysis; the page does not claim experimental confirmation of the model.
