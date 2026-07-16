# Einstein--Matter Coupling from Spectral Stationarity

This repository contains the source of *Einstein--Matter Coupling from Spectral
Stationarity: A Conditional Variational Result and the Open Thermodynamic Bridge*.

This note separates a conditional variational identity from a thermodynamic reading that is
not established.

## Conditional variational result

Let

\[
S_\Pi^{\mathrm{ren}}[g]
= \frac12\log\det'\!\left(A_g/\mu^2\right)
\]

be the renormalized projective spectral functional, and let
\(W_\Pi[g,\psi]\) be an independently defined effective matter functional.
If the leading infrared metric response of \(S_\Pi^{\mathrm{ren}}\) contains specified
renormalized Einstein and cosmological terms, stationarity of

\[
\Gamma_\Pi=S_\Pi^{\mathrm{ren}}-W_\Pi
\]

yields

\[
G_{\mu\nu}+\Lambda_{\mathrm{ren}}g_{\mu\nu}
=8\pi G_N T^{(\Pi)}_{\mu\nu}
\]

at leading local derivative order.
The coefficient is the ratio

\[
\frac{1/2}{(16\pi G_N)^{-1}}=8\pi G_N.
\]

This is a conditional joint geometric--matter variational statement.
The companion Gravity paper separates the spectral-cutoff and zeta sectors and treats the
finite Einstein coefficient as a matching datum.
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

A thermodynamic completion requires: an independently defined heat one-form, a Lorentzian energy notion, an
operational temperature calibration, and an integrability theorem establishing
\(\delta Q=T\,\mathrm dS\).

## Core claims

- The diagonal heat kernel defines a local spectral rate and a dimensionless normalized
  curvature response.
- Joint stationarity of the geometric and matter functionals yields the infrared
  Einstein--matter equation under explicit renormalization hypotheses.
- Once the renormalized Einstein coefficient is supplied, the factor \(8\pi G_N\)
  follows from a ratio of variation coefficients.
- A thermodynamic interpretation remains open and is not used in the proof.

## Keywords

Spectral determinant, heat kernel, induced gravity, Einstein equation, matter coupling,
variational principle, thermodynamic integrability

## Links

- [Programme website](https://cosmochrony.org/science/spectral-gravity/thermodynamics/)
- [Zenodo concept DOI](https://doi.org/10.5281/zenodo.18825655)

## Citation

> J. Beau, *Einstein--Matter Coupling from Spectral Stationarity: A Conditional Variational Result
> and the Open Thermodynamic Bridge*, 2026.

## Acknowledgements

Portions of the development benefited from iterative interactions with large language
models used as analytical assistants.
All claims, interpretations, and final formulations remain the author's responsibility.
