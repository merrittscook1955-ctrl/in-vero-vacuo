# Methods & Tools

## Overview
The methods developed in In Vero Vacuo form a modern computational pipeline for
evaluating fluctuation determinants in scalar and gauge theories. These tools
extend beyond traditional O(4) symmetry assumptions and are designed to operate
reliably in multi‑field potentials, finite‑temperature backgrounds, curved
spacetimes, and gauge theories with nontrivial structure.

The approach combines validated SU(2) lattice machinery, nonlinear vertex
construction, and stochastic‑Lanczos trace‑log evaluation to produce accurate,
reproducible decay‑rate prefactors.

---

## Lattice Determinant Pipeline
The determinant pipeline is built around a sequence of validated components:

- **Nonlinear SU(2) vertex generation**  
  Constructs gauge, Goldstone, and ghost vertices with correct nonlinear
  structure for semiclassical backgrounds.

- **Exact Hessian construction**  
  Builds scalar, gauge, Goldstone, and ghost fluctuation operators with
  full nonlinear dependence on the background configuration.

- **Stochastic‑Lanczos trace‑log evaluation**  
  Computes the trace‑log of large sparse operators using deflated stochastic
  Lanczos methods, enabling efficient determinant evaluation.

- **Bounce relaxation and probe ensembles**  
  Generates background configurations and probe ensembles with reproducibility
  guarantees for cross‑checks and validation.

- **Routing and projector deck**  
  Provides a complete set of operator projectors and routing rules for
  consistent gauge‑theory matching.

---

## Matching Infrastructure
To ensure consistency between lattice and continuum calculations, the project
implements a structured matching framework:

- **Scalar and gauge vertices**  
  Full nonlinear vertex sets for both scalar and gauge sectors.

- **Operator projectors**  
  Projectors for isolating gauge, Goldstone, and ghost contributions.

- **Regulated Brillouin‑zone integrals**  
  Momentum‑space integrals performed with lattice‑appropriate regulators.

- **Continuum MS amplitudes**  
  Reference amplitudes computed in the MS scheme for comparison.

- **Finite lattice–minus–MS differences**  
  Systematic evaluation of lattice–continuum differences to ensure consistency.

---

## Validation Suite
Every component of the pipeline is validated through a series of checks:

- **Momentum conservation**  
- **Gauge‑invariance Ward identities**  
- **Ghost‑Jacobian consistency**  
- **Hessian agreement across sectors**  
- **Nonzero‑background FP matrix tests**  
- **Full routing/projector audit**

These checks ensure that the machinery behaves correctly across a wide range of
backgrounds and parameter choices.

---

## Related Pages
- [Research Overview](research.md)  
- [Results](results.md)  
- [Reports](reports.md)  
- [About](about.md)  
- [Collaborators](collaborators.md)  
- [News & Updates](news.md)
