This repository contains the source of the  
paper on local spectral thermodynamics and gravitational equilibrium  
(paper I de Cosmochrony / paper 2 de gravity).

This work develops a **local thermodynamic interpretation of spectral geometry**
based on the projective entropy functional

$S_\Pi[g] = \tfrac12 \log \det{}' A_g$.

Starting from the diagonal heat kernel, we define a **local spectral energy
density**

$u(x;t) = -\partial_t \log K(x,x;t)$,

whose Seeley–DeWitt expansion yields a **local multiplier field**

$\beta(x)^{-1} = \beta_0^{-1} - \tfrac16 R(x) + O(\nabla^2 R)$.

We then show that:

- a local spectral first law arises as a **compatibility condition** between
  the geometric and matter variations,
- Einstein’s equation emerges as the 
  [Euler–Lagrange condition](https://en.wikipedia.org/wiki/Euler%E2%80%93Lagrange_equation) of a
  constrained extremum of the spectral entropy,
- the factor ($8\pi G$) follows uniquely from independent normalization conventions.

The derivation requires **no horizon structure, no [Rindler wedge](https://en.wikipedia.org/wiki/Rindler_coordinates),
no [Raychaudhuri equation](https://en.wikipedia.org/wiki/Raychaudhuri_equation)**, and no thermodynamic postulate.
Einstein’s equation appears as a **spectral equilibrium condition** in the
infrared-dominant regime.

## Conceptual Overview

The paper proceeds in three logical steps:

1. **Spectral locality**  
   The diagonal heat kernel defines a local spectral energy density whose
   short-time expansion produces a curvature-dependent multiplier field.
   The universal part $\beta_0^{-1} = 2/t_*$ depends on the spectral
   admissibility scale $t_*$, which is a resolution parameter rather than a
   physical temperature.

2. **Local spectral first law (compatibility condition)**  
   The projected matter energy $E_\Pi$ is defined independently from the effective matter action.
   In the infrared regime, the metric variation of the renormalized spectral entropy satisfies

   $\delta S_\Pi = \int \beta(x)^{-1} \delta E_\Pi(x)$,

   not as a definition, but as a structural equivalence condition.
   This identity holds if and only if the geometry satisfies Einstein’s equation at leading order.

3. **Spectral equilibrium principle**  
   Admissible geometries extremize

   $\mathcal{F}[g,\psi] = S_\Pi[g] - \vartheta_*^{-1} W_\Pi[g,\psi]$,

   where \(W_\Pi\) is the projected matter functional and $\vartheta_*^{-1}$ is the global
   matter–geometry multiplier (kept notationally distinct from the local spectral field
   $\beta(x)^{-1}$ and from the spectral-admissibility cascade exponent $\beta^*$).
   The [Euler–Lagrange condition](https://en.wikipedia.org/wiki/Euler%E2%80%93Lagrange_equation) of this constrained 
   extremum yields

   $G_{\mu\nu} = 8\pi G_N T_{\mu\nu}$.

   The numerical factor $8\pi G_N$ arises solely from the product of
   geometric and matter normalization conventions.

   In the gauge sector, $\vartheta_*^{-1} = 1$ is identified conditionally as the
   *single-determinant value* fixed by the relative $a_2/a_4$ normalization of the joint spectral
   functional (Q13). The off-equilibrium term $\vartheta_*^{-1} \neq 1$ renormalizes the coupling to the
   same matter content rather than defining an independent fluid, and the $a_2$ channel is classically
   silent for traceless radiation.

## Core Claims

The paper establishes the following statements:

1. **The heat kernel defines a local spectral multiplier field**  
   The Seeley–DeWitt coefficient $a_2 = \tfrac16 R\$ controls the leading
   geometric correction to the local spectral temperature multiplier.

2. **The local spectral first law is a compatibility identity**  
   The relation $\delta S_\Pi = \int \beta^{-1} \delta E_\Pi$ is not a
   thermodynamic postulate but a structural condition linking geometric and
   matter variations.

3. **Einstein’s equation is an extremum condition**  
   The field equation arises from a constrained variational principle on the
   spectral entropy functional.

4. **The factor ($8\pi G$) is fixed by normalization alone**  
   It results from combining the geometric normalization
   $(16\pi G)^{-1}$ with the stress-tensor definition factor $1/2$.
   No additional parameter is introduced.

5. **No causal or horizon assumptions are required**  
   The derivation is performed entirely on Riemannian manifolds.
   Horizons and Unruh temperature enter only as formal analogies, not as
   foundational ingredients.

## What This Paper Does Not Assume

To avoid conflating structural and thermodynamic claims, the paper does not assume:

- the existence of local Rindler horizons,
- the Clausius relation $\delta S = \delta Q/T$,
- a microscopic thermodynamic interpretation,
- local Lorentz invariance at the Planck scale,
- any modification of classical general relativity.

The analysis is entirely spectral and variational.

## Keywords

Spectral entropy, heat kernel, Seeley–DeWitt expansion, induced gravity,
Einstein equation, spectral equilibrium, local temperature multiplier,
variational principle

## Repository Contents

```
paper/
├── pdf/ # Compiled paper PDF
├── tex/ # LaTeX sources
└── README.md
```

## Links

- 📄 [Paper PDF](https://github.com/Cosmochrony/thermodynamics-paper/blob/main/pdf/Thermodynamics.pdf)
- 🌐 Website: [cosmochrony.org](https://cosmochrony.org)

## Citation

If you reference this work, please cite:

> J. Beau, *Local Spectral Thermodynamics and the Einstein Equation as a Spectral Equilibrium Condition*, 2026.

## Acknowledgements

Portions of the editorial refinement benefited from iterative interactions with
large language models.
These tools were used as analytical assistants for exploring alternative
formulations, checking internal consistency, and improving clarity.
All claims, interpretations, and final formulations remain the sole
responsibility of the author.

## Contributions

This repository is intended as a research reference.

Critical feedback, independent analyses, and formal scrutiny are welcome.
Please open an issue to discuss conceptual points, normalization choices,
possible counterexamples, or alternative formulations.
