# PRECON

> **A historical archive.** PRECON is no longer maintained and will not run on
> modern operating systems. It is preserved here for the historical record.

PRECON — *"A Statistical Model for Analyzing the Tree-Ring Response to Variations
in Climate"* — is a program by **Harold C. Fritts** of the Laboratory of Tree-Ring
Research (LTRR), University of Arizona. This repository preserves **version 5.17**
and its documentation for posterity.

PRECON computes **response and correlation functions** relating tree-ring growth
to monthly climate variables (temperature and precipitation). It supports stepwise
multiple regression and, preferably, **bootstrapped response functions** (after
Guiot, 1991, *Tree-Ring Bulletin* 51:39–41), which give more reliable estimates of
significance in the presence of collinearity among climate predictors.

## Why this matters

Harold C. Fritts was a foundational figure in dendroclimatology; his 1976 book
*Tree Rings and Climate* defined the field. PRECON implemented the
response-function methodology at the heart of that work, letting researchers
quantify and test the climate signal recorded in tree-ring chronologies. The
approach it pioneered continues today in modern tools such as the `treeclim` and
`bootRes` R packages and [dplR](https://opendendro.org/r/).

## Contents

- `Hal_precon.mhtml` — the original PRECON web page describing the method, with a
  worked example (Walnut Canyon ponderosa pine chronology vs. monthly climate)
- `PRECON Downloading Information.mhtml` — the original download page
- `preco517.zip` — PRECON, version 5.17
- `prconcld.zip`, `prconpcn.zip` — PRECON builds / components
- `kalman.zip`, `newprdat.zip` — related utilities and data

## Provenance

Written by **Harold C. Fritts**, Laboratory of Tree-Ring Research, University of
Arizona. Distributed historically from `www.ltrr.arizona.edu/~hal/`.

## License & use

See [`LICENSE`](LICENSE). This material is provided **as-is, for historical and
educational purposes, with no warranty**.
