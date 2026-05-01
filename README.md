This paper establishes that the admissible sector in the Cosmochrony spectral
programme is *spectrally atomic*: each conjugate pair spans exactly three pure
Fourier modes. This result closes key analytical gaps in Q5a by removing the
need for Nash-type inequalities and completing the control of admissibility
forms.

## Quick Summary

- **Spectral atomicity**: each admissible pair is supported on exactly three pure Fourier modes
- **No-mode-mixing**: admissible fingerprints behave as single-frequency eigenmodes
- **Closure of hypotheses**:
    - closes [H-E1] (uniform Poincaré on admissible sector)
    - closes [C] (spectral tightening → Mosco convergence)
- **Elimination of Nash inequalities**: replaced by exact Fourier structure
- **Structural refinement of Q5a**: strengthens convergence results without additional assumptions

## Main Results

### 1. Atomic Fourier structure

Each admissible fingerprint vector is concentrated on a single frequency:

- empirical concentration: $R_{99\%} = 1$
- no dispersion across modes

This implies:

- exact diagonalisation of the admissibility form
- absence of hidden mixing effects

### 2. Three-mode structure per conjugate pair

For each pair $\{c, q-c\}$:

- admissible subspace:
  $\mathrm{span}\{ e_0, e_{\xi_c}, e_{\xi_c}^\ast \}$
- dimension:
  $\dim H_{\text{eff}} = 3$

This matches the structural result:

- $\Sigma_c(n_3) = 3$ (O23)
- rank $r_{\mathrm{eff}} = 3$ (O28)

### 3. Closure of analytical hypotheses

The atomic structure implies:

- **[H-E1] (Poincaré inequality)**  
  → holds automatically on each frequency block

- **[C] (spectral tightening)**  
  → follows from exact mode separation

Thus:

- Mosco convergence becomes structurally controlled
- no functional-analytic workaround (e.g. Nash) is needed

### 4. Structural interpretation

Admissibility does not produce a diffuse spectrum but a **minimal discrete support**:

- one neutral mode
- one conjugate pair of oscillatory modes

This defines the admissible sector as a **minimal coherent triplet**, not a continuum.

## Context in the Programme

Q5a establishes convergence of admissibility forms to a continuum operator:

- Hilbert limit $\mathbb{C}_q \to L^2(\mathbb{R})$
- Mosco convergence of $\mathcal{E}_q \to \mathcal{E}$

Q5a-O2 strengthens this by proving:

- the admissible sector is already **fully resolved spectrally**
- no hidden degrees of freedom remain at the discrete level

This aligns with:

- O23: quaternionic minimality → 3 directions
- O28: effective dimension $r_{\mathrm{eff}} = 3$
- Q7: identification $H_{\text{eff}} \simeq \mathrm{Sym}^2(V_\rho)$

## Conceptual Implications

- **Admissibility = spectral selection, not diffusion**
- **Emergence is low-rank, not high-dimensional**
- **Continuum limit acts on already minimal structures**

This supports the core principle:

> Observable structure lives in $\mathrm{Im}\,\Pi$, not in the full configuration space.

## Numerical Evidence

- primes tested: $q = 29, 61, 101, 151$
- all conjugate pairs:
    - exact single-frequency dominance
    - no rank inflation
    - strict monotonicity of admissible projections

## Keywords

spectral atomicity, admissible projection, Fourier modes,  
Dirichlet forms, Mosco convergence, Heisenberg group,  
Weil representation, spectral gap, finite-dimensional reduction
