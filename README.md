# Einstein--Matter Coupling from Spectral Stationarity

This repository contains the source of *Einstein--Matter Coupling from Spectral
Stationarity: Established Result and the Open Thermodynamic Bridge*.

Version 2.0 separates a robust variational result from thermodynamic claims that were
not established in version 1.1.

## Established result

Let

\[
S_\Pi^{\mathrm{ren}}[g]
= \frac12\log\det'\!\left(A_g/\mu^2\right)
\]

be the renormalized projective spectral functional, and let
\(W_\Pi[g,\psi]\) be an independently defined effective matter functional.
If the leading infrared metric response of \(S_\Pi^{\mathrm{ren}}\) is the Einstein
tensor, stationarity of

\[
\Gamma_\Pi=S_\Pi^{\mathrm{ren}}-W_\Pi
\]

yields

\[
G_{\mu\nu}=8\pi G_N T^{(\Pi)}_{\mu\nu}
\]

at leading local derivative order.
The coefficient is the ratio

\[
\frac{1/2}{(16\pi G_N)^{-1}}=8\pi G_N.
\]

This is a joint spectral--matter variational statement.
It is not, by itself, a thermodynamic equilibrium theorem.

## Local spectral response

For the minimal scalar Laplacian in four dimensions,

\[
u(x;t)=-\partial_t\log K(x,x;t)
=\frac2t-\frac16R(x)+O(t\mathcal R^2,t\nabla^2R).
\]

Because \([t]=L^2\), the spectral rate has dimension \([u]=L^{-2}\).
Its normalized form is

\[
b(x;t)=\frac{tu(x;t)}2
=1-\frac{tR(x)}{12}+O(t^2\mathcal R^2,t^2\nabla^2R).
\]

The quantity \(b\) is a dimensionless curvature response.
Neither \(u\) nor \(b\) is identified with a physical temperature, inverse
temperature, or energy density.

## Status correction relative to version 1.1

Version 2.0 withdraws the following claims of version 1.1:

1. that \(-\partial_t\log K\) is a local energy density or temperature;
2. that the diagonal heat kernel establishes a local first law;
3. that local metric variations replace a constant coupling by a
   curvature-dependent temperature field;
4. that the variational Einstein equation is thereby proved to be an equilibrium
   equation of state.

The corrected paper explains the additional structures required for a thermodynamic
completion: an independently defined heat one-form, a Lorentzian energy notion, an
operational temperature calibration, and an integrability theorem establishing
\(\delta Q=T\,\mathrm dS\).

## Core claims

- The diagonal heat kernel defines a local spectral rate and a dimensionless normalized
  curvature response.
- Joint stationarity of the spectral and matter functionals yields the infrared
  Einstein--matter equation under explicit hypotheses.
- The factor \(8\pi G_N\) follows from a ratio of variation coefficients.
- A thermodynamic interpretation remains open and is not used in the proof.

## Keywords

Spectral determinant, heat kernel, induced gravity, Einstein equation, matter coupling,
variational principle, thermodynamic integrability

## Links

- [Paper PDF](https://github.com/Cosmochrony/thermodynamics-paper/blob/main/out/Thermodynamics.pdf)
- [Programme website](https://cosmochrony.org/science/spectral-gravity/thermodynamics/)
- [Zenodo concept DOI](https://doi.org/10.5281/zenodo.18825655)

## Citation

> J. Beau, *Einstein--Matter Coupling from Spectral Stationarity: Established Result
> and the Open Thermodynamic Bridge*, 2026.

## Acknowledgements

Portions of the development benefited from iterative interactions with large language
models used as analytical assistants.
All claims, interpretations, and final formulations remain the author's responsibility.
