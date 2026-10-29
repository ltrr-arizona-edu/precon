# PRECON

> **A historical archive.** PRECON is no longer maintained and will not run on
> modern operating systems. It is preserved here for the historical record.

PRECON — *"A Statistical Model for Analyzing the Tree-Ring Response to Variations
in Climate"* — is a program by **Harold C. ("Hal") Fritts** of the Laboratory of
Tree-Ring Research (LTRR), University of Arizona. This repository preserves two
versions: **5.17** and the final **version 6.0 (PRECON6, 2009)**, together with
their documentation.

PRECON computes **response and correlation functions** relating tree-ring growth
to monthly climate variables (temperature and precipitation). It supports stepwise
multiple regression and, preferably, **bootstrapped response functions** (after
Guiot, 1991, *Tree-Ring Bulletin* 51:39–41), which give more reliable estimates of
significance in the presence of collinearity among climate predictors.

## PRECON6 (2009) — the final version

By 2009, Fritts streamlined PRECON around the capability that had remained its most
enduring contribution — the response function. In the note accompanying PRECON6
(`README6_PRECON.txt`, 29 June 2009) he wrote: *"I have assumed that now the only
interest in this program is the RESPONSE FUNCTION."* For this release he revised and
checked the default analysis (**option 1**) and the option that computes the
**bootstrapped response function** from user-supplied files (**option 5**), along
with the program's learning mode. He cautioned that the program's other options were
not revisited for this version and may not run correctly. PRECON6 is the last
version Fritts released.

## Why this matters

Harold C. Fritts was a foundational figure in dendroclimatology; his 1976 book
*Tree Rings and Climate* defined the field. PRECON implemented the response-function
methodology at the heart of that work, letting researchers quantify and test the
climate signal recorded in tree-ring chronologies. The approach it pioneered
continues today in modern tools such as the `treeclim` and `bootRes` R packages and
[dplR](https://opendendro.org/r/).

## Contents

- `Hal_precon.mhtml` — the original PRECON web page describing the method, with a
  worked example (Walnut Canyon ponderosa pine chronology vs. monthly climate)
- `PRECON Downloading Information.mhtml` — the original download page
- `PRECON6.exe` — PRECON version 6.0 (2009), the final release
- `README6_PRECON.txt` — Hal Fritts's note accompanying PRECON6
- `preco517.zip` — PRECON version 5.17
- `prconcld.zip`, `prconpcn.zip` — earlier PRECON builds / components
- `kalman.zip`, `newprdat.zip` — related utilities and data

## Provenance

Written by **Harold C. Fritts**, Laboratory of Tree-Ring Research, University of
Arizona. Distributed historically from `www.ltrr.arizona.edu/~hal/`. The PRECON6
release note (2009) was addressed to the program's longtime users.

## License & use

See [`LICENSE`](LICENSE). This material is provided **as-is, for historical and
educational purposes, with no warranty**.
