# Technical Reports

This page collects formal progress reports, validation summaries, and source
bundles associated with the In Vero Vacuo lattice determinant pipeline. Each
report documents a specific milestone in the development of scalar and SU(2)
gauge machinery, matching infrastructure, and determinant evaluation tools.

---

## Progress Reports

### SU(2) Matching-Coefficient Progress Report — Oct 6, 2026
A detailed summary of the SU(2) matching infrastructure, including:
- Nonlinear gauge and Goldstone vertex construction  
- Projector and routing validation  
- Regulated Brillouin-zone integral tests  
- Preliminary lattice–MS finite-difference comparisons  

This report establishes the foundation for full gauge-sector matching.

---

### Finite Lattice-to-MS Matching: Scalar Sector — Oct 7, 2026
Covers scalar-sector matching and renormalization consistency:
- Complete scalar radial matching coefficients  
- Nonlinear scalar vertex deck verification  
- MS reference amplitudes  
- Finite lattice–minus–MS difference evaluation  

This report confirms scalar-sector consistency across lattice spacings.

---

### Regulated One-Loop Sector Checks (SU(2)) — Oct 8, 2026
Documents the first full one-loop gauge-sector checks:
- Gauge, Goldstone, and ghost operator construction  
- Ward-identity validation  
- Ghost-Jacobian consistency tests  
- Multi-point gauged amplitude prototypes  

These results validate the nonlinear SU(2) machinery under nontrivial backgrounds.

---

### L = 30 Bare-Lattice Determinant Run Report — Oct 9, 2026
Large-lattice determinant run summary:
- Relaxation RMS: **3.27 × 10⁻¹²**  
- Bare logdet ratio: **−2057.27 ± 5.9**  
- 16 probes, 60 Lanczos steps  
- 12 deflated modes per channel  
- Full reproducibility archive generated  

These bare finite-lattice results form the baseline for continuum comparison.

---

### Higgs Fluctuation Solver — Technical Summary
A dedicated module for constructing and evaluating Higgs-sector fluctuation
operators in semiclassical backgrounds.

Key features:
- Full nonlinear Higgs-sector Hessian construction  
- Goldstone/Higgs mixing handled through exact operator decomposition  
- Probe ensemble support for determinant evaluation  
- Verified consistency with SU(2) gauge-sector operators  
- Ready for multi-field metastability case studies  

This solver forms the backbone of Higgs-sector determinant calculations.

---

### Determinant Ratio Calculator — Technical Summary
A specialized tool for computing determinant ratios between background and
reference configurations, enabling clean extraction of decay-rate prefactors.

Capabilities:
- SLQ-based trace-log ratio evaluation  
- Automatic deflation of shared modes  
- Background/reference operator alignment  
- Statistical uncertainty estimation from probe ensembles  
- Full reproducibility logging  

This calculator provides the final step in assembling semiclassical decay-rate
prefactors.

---

## Source Bundles

### Nonlinear SU(2) Vertex Module
Complete nonlinear vertex sets for gauge, Goldstone, and ghost sectors, including
routing rules and projector definitions.

### Bounce Relaxation Solver
Background-configuration generator with reproducibility guarantees and probe
ensemble support.

### SLQ Determinant Pipeline
Stochastic-Lanczos trace-log machinery for large sparse operators, including
deflation, probe management, and convergence diagnostics.

### Routing/Projector Deck
Full routing and projector infrastructure for scalar and gauge sectors, validated
against Ward identities and Hessian consistency tests.

### Reproducibility Archives (SHA-256 Verified)
Complete archives for determinant runs, matching tests, and validation suites,
including probe ensembles, relaxation logs, and operator snapshots.

---

## Related Pages
- [Research Overview](research.md)
- [Methods & Tools](methods.md)
- [Results](results.md)
- [About](about.md)
- [Collaborators](collaborators.md)
- [News & Updates](news.md)
