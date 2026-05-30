## Overall Roadmap

Following MIT linear PDE courses, PDE study centers on the heat equation, wave equation, and Laplace equation, with core techniques such as well-posed problems, separation of variables, eigenfunction expansions, and Green's functions. This repository is organized around wave equations, heat conduction, and harmonic functions.

```text
Partial Differential Equations = describing change across space and time
|
+-- The central problems
|   +-- How do physical processes become equations?
|   |   +-- Derive PDEs and conditions from vibrating strings, heat conduction, and harmonic fields.
|   +-- How are initial-boundary value problems solved?
|   |   +-- Use d'Alembert's formula, separation of variables, Fourier methods, and Green functions.
|   +-- Are solutions unique, stable, and physically meaningful?
|       +-- Use energy estimates, maximum principles, asymptotics, and Huygens' principle.
|
+-- Tool 1: well-posed problems -> equation + initial data + boundary data
|   +-- Derivation of equations  obtain PDEs from conservation laws or geometric structure
|   +-- Conditions               specify initial states and boundary constraints
|   +-- Well-posedness           existence, uniqueness, and stability
|
+-- Tool 2: wave equation -> propagation and vibration
|   +-- Vibrating string equation source of the one-dimensional wave model
|   +-- d'Alembert's formula     explicit left-right wave propagation
|   +-- Separation of variables  separate space and time
|   +-- Higher-dimensional Cauchy problems use spherical means and descent
|   +-- Energy estimates         control uniqueness and stability
|
+-- Tool 3: heat equation -> diffusion and smoothing
|   +-- Derivation of the heat equation from diffusion and conservation
|   +-- Initial-boundary problems solved through separation and Fourier expansion
|   +-- Cauchy problems described by heat kernels
|   +-- Maximum principle controls solutions through extrema
|
+-- Tool 4: harmonic functions -> equilibrium and boundary problems
    +-- Laplace / Poisson viewpoint describe steady spatial distributions
    +-- Green identities           connect interior and boundary information
    +-- Green functions            build representation formulas for boundary problems
```

# dx's Partial Differential Equations

## Preface

This book has the feeling of a real study battlefield. PDEs are not mastered only by calmly reading definitions; they are gradually opened through lectures, homework, review, exam pressure, and repeated calculation.

Wave equations, heat equations, d'Alembert's formula, separation of variables, Green identities, maximum principles, and energy methods are familiar names, but the order of attack can easily become confused in actual problems.

## Why This Book Is Written This Way

The hard part of this course is often not pure ignorance, but disorder. A reader may know several methods but not know which one to use first.

The notes therefore preserve many direct reminders about procedure: write the standard formula first, proceed step by step, identify the type of problem, then decide whether to use separation of variables, an energy method, an influence region, or a boundary formula.

## What This Book Keeps

The first chapter centers on the wave equation: derivation, conditions, d'Alembert's formula, propagation, and higher-dimensional Cauchy problems. The second part moves into heat conduction, separation of variables, maximum principles, heat kernels, and Green formulas.

Homework solutions, compressed review notes, and exam-oriented summaries are part of the structure rather than secondary material. They show how the theory is actually used.

## Intended Readers

This book is for readers who feel disorganized when facing PDE problems. Its goal is to build an internal order: classify the problem, stabilize the method, then calculate.

## Repository Notes

- The main entry is `main.tex`.
- The main files cover wave equations, heat conduction, homework analysis, review notes, and exam-oriented material.
- A compiled PDF is also kept in the repository.
- For local compilation, running `xelatex main.tex` twice is usually enough.
