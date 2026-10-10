# Phase 0 · Classical Mechanics

These lessons cover the classical mechanics part of the Phase 0 refresher in [qft-study-plan.md](../../qft-study-plan.md). Each lesson takes about 2–3 hours plus exercises, and full solutions are at the end of each one.

| # | Lesson | Covers | Sets up (Lancaster & Blundell) |
|---|--------|--------|------------------------------|
| 1 | [cm01-lagrangians.pdf](cm01-lagrangians.pdf) | Action, Euler–Lagrange equations, worked examples, normal modes, from a chain of masses to a field, Klein–Gordon | ch. 1, 5, 7 |
| 2 | [cm02-hamiltonians.pdf](cm02-hamiltonians.pdf) | Legendre transform, Hamilton's equations, phase space, Poisson brackets, classical ladder variables, Dirac quantization, field Hamiltonians | ch. 2–4, 11 |
| 3 | [cm03-noether.pdf](cm03-noether.pdf) | Noether's theorem for particles and fields, charges as generators, U(1) current, energy–momentum tensor, preview of gauging | ch. 10, 12, 14 |

**Conventions** (shared through `qftnotes.sty`):
- metric signature (+,−,−,−)
- ħ = c = 1 for fields
- Poisson bracket {q, p} = +1, so dA/dt = {A, H} + ∂A/∂t

## Rebuilding the PDFs

Run this from this folder:

```
tectonic cm01-lagrangians.tex
```

Tectonic is installed in `%LOCALAPPDATA%\Programs\tectonic` and is on your user PATH. Any standard LaTeX install works too, e.g. Overleaf: upload the `.tex` file together with `qftnotes.sty`.
