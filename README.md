# FYB_Enzyme_Kinetics

An interactive tool to understand enzyme–substrate interactions.

## Live demo

Once GitHub Pages is enabled for this repository, the interactive is served at:

**https://reecesophoc.github.io/fyb_enzyme_kinetics/**

## About

`index.html` is a self-contained interactive for **BIOL1XX7 — Enzyme Kinetics: Measuring Reaction Rate**.
It lets students explore why an enzyme progress curve bends, why kinetics uses the **initial rate**, and how
the **amount of enzyme** and **amount of substrate** each change the result.

Features:
- Adjustable enzyme concentration `[E]`, substrate concentration `[S]`, and measurement window `Δt`.
- Animated "Run assay" progress curve (Michaelis–Menten with substrate depletion, integrated with RK4).
- Overlays for the **true initial rate** (tangent, v₀) vs the **measured average rate** (chord, ΔP/Δt).
- Pin-a-curve comparison and live teaching captions that update with the measurement window.

The page is a single HTML file with no external dependencies, so it runs offline and on GitHub Pages as-is.

## Enabling GitHub Pages

If Pages is not yet turned on: in the repository, go to **Settings → Pages**, set **Source** to
**Deploy from a branch**, choose branch `main` (or this branch) and folder `/ (root)`, then save.

_Designed by Dr Reece Sophocleous · The University of Sydney — First Year Biology._
