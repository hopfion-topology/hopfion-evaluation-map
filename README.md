# Hopfion Evaluation Map

Interactive computational companion for the paper:

**Hopfion Topology, Quantum Geometric Tensor Saturation, and the Fine-Structure Constant**

## What is this?

The polynomial f(x) = 4x³ + x² + x, with coefficients (4,1,1) proposed to be fixed by SU(2) topology, outputs the fine-structure constant α⁻¹ ≈ 137.036 when evaluated at π — with zero free parameters.

This calculator lets you:
- **Explore all 8 distinguished evaluations** via the interactive nautilus shell
- **Tour** through each evaluation with the guided walkthrough
- **Try your own inputs** with the polynomial explorer (forward and inverse)
- **Examine framework predictions** including the Connes trace convergence, Faddeev-Niemi mass spectrum, and R(k) metric-dominance diagnostic

## Deploy

Single-file application. Open `index.html` in any browser, or deploy to GitHub Pages:

1. Push this repo to GitHub
2. Settings → Pages → Source: main branch, root folder
3. Live at `https://yourusername.github.io/repo-name/`

## Files

- `index.html` — Complete standalone app (React via CDN, no build step)
- `hopfion_v31.jsx` — Raw React component source for editing
- `README.md` — This file

## Math verified

Every number in this calculator has been independently verified by computation. All 8 evaluations, Connes trace convergence, mass spectrum scaling, and R(k) diagnostic are mathematically confirmed.

## Links

- **Paper:** [doi.org/10.5281/zenodo.19394164](https://doi.org/10.5281/zenodo.19394164)
- **This calculator (all versions):** [doi.org/10.5281/zenodo.19452185](https://doi.org/10.5281/zenodo.19452185)

## License

MIT