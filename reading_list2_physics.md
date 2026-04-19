# Physics Reading List

Prioritize books that build deep physical intuition and derive results from first principles — not formula sheets.
Style benchmarks: Feynman Lectures (physical reasoning), Sakurai (formalism-first rigor), Carroll (motivated geometry).

Goals:

* Achieve PhD-level understanding of modern physics — not just applying equations, but understanding *why* the laws take the form they do.
* Deep mastery of general relativity, quantum mechanics, quantum field theory, and particle physics.
* Long-term: understand the landscape of string theory and quantum gravity as active research areas.
* Avoid recipe books. Derive, prove, and understand.

## Math Prerequisites (from reading_list.md)

Physics stages map to math stages as follows. Do not start a physics stage before the math prereqs are in hand.

| Physics Stage | Required Math (reading_list.md) |
|---|---|
| Stage 1 | Math Stage 1 (linear algebra, proofs) + Stage 2 Track E (ODEs) + Hubbard & Hubbard (vector calculus) |
| Stage 2 | Math Stage 2 complete (complex analysis, Fourier, topology) |
| Stage 3 | Math Stage 3 Tracks B (functional analysis) + G (Lie groups) + beginning of C (differential geometry) |
| Stage 4 | Math Stage 3 Track C complete (Lee, Do Carmo, Needham) |
| Stage 5 | Math Stage 3 fully complete (all tracks) |
| Stage 6 | Physics Stage 5 complete + Math Stage 3 Track D (algebraic topology) |

---

## Stage 1: Classical Physics

Math prereqs: Math Stage 1 + ODEs (Stage 2 Track E) + vector calculus (Hubbard & Hubbard).

Books within the same track are sequential. Different tracks can be read in parallel.

### Track A: Companion — Read Throughout

- [ ] The Feynman Lectures on Physics (Vols. 1–3), by Feynman, Leighton, and Sands
  - Not a textbook — a masterpiece of physical reasoning. Vol. 1: mechanics, thermodynamics. Vol. 2: electromagnetism. Vol. 3: quantum mechanics. Read alongside the formal texts in each stage for the physical intuition that formal books often suppress. Every derivation is motivated by a physical question. Available free online.

### Track B: Classical Mechanics

- [ ] Classical Mechanics, by John R. Taylor
  - The best undergraduate mechanics text. Rigorous and full of motivated examples. Covers Newtonian mechanics, oscillations, Lagrangian and Hamiltonian mechanics, central force problems, rigid body motion. The Lagrangian formalism here is the seed of all field theory — understand it deeply.
  - Emphasize: Ch 1-7 (core mechanics), Ch 13-14 (Hamiltonian mechanics) — these are the most important for later stages. Ch 10-12 (rigid bodies, coupled oscillators) are useful but less critical.

### Track C: Electrodynamics

- [ ] Introduction to Electrodynamics, by David Griffiths
  - The standard rigorous undergraduate EM text. Derives Maxwell's equations cleanly, covers electromagnetic waves, potentials, radiation, and special relativity (Ch 12). Requires vector calculus — every identity is derived, not asserted.
  - Emphasize: Ch 1-10 (core EM). Ch 11 (radiation) and Ch 12 (relativistic EM) are important bridges to field theory.

---

## Stage 2: Special Relativity and Quantum Mechanics

Math prereqs: Math Stage 2 complete (complex analysis, Fourier, ODEs, linear algebra fully done).

### Track A: Special Relativity

- [ ] Spacetime Physics, by Edwin Taylor and John Wheeler
  - Geometrical, intuitive, and example-driven. Builds the spacetime interval and 4-vector formalism from first principles with genuine insight. Essential conceptual foundation before general relativity — GR is just SR with curvature, so if SR isn't clear and visual, GR won't be either.
- [ ] Special Relativity and Classical Field Theory: The Theoretical Minimum, by Susskind and Hrabovsky
  - Susskind's "Theoretical Minimum" series is ideal for the style of this list: lectures that derive everything and explain the *why*. This volume bridges SR directly to Lagrangian field theory — the language of all of modern physics. Read after Taylor & Wheeler.

### Track B: Quantum Mechanics — Undergraduate

- [ ] Introduction to Quantum Mechanics, by David Griffiths
  - The standard first QM text. Derives the Schrödinger equation, solves the hydrogen atom, covers the formalism (Hilbert space, operators, observables), perturbation theory, and identical particles. Requires ODEs and linear algebra. Read alongside Feynman Vol. 3 for physical motivation.
  - Emphasize: Ch 1-6 (core formalism and exactly solvable systems). Ch 7-11 (approximation methods) are critical for the transition to Sakurai.

---

## Stage 3: Graduate Classical and Quantum Mechanics

Math prereqs: Math Stage 3 Track B (functional analysis: Kreyszig) + Track G (Lie groups: Hall) + beginning of Track C (Do Carmo).

Books within the same track are sequential. Different tracks can be read in parallel.

### Track A: Analytical Mechanics

- [ ] Mechanics, by Landau and Lifshitz (Course of Theoretical Physics, Vol. 1)
  - Extremely terse and demanding, but more insightful per page than almost any other physics text. Derives all of classical mechanics from the principle of least action. Every result follows from a variational argument. Read after Taylor — Taylor teaches the tools, Landau shows why they are inevitable.
  - Companion: Work every problem. The problems are part of the text.
- [ ] Classical Theory of Fields, by Landau and Lifshitz (Course of Theoretical Physics, Vol. 2)
  - Covers special relativity, classical field theory (Lagrangian and Hamiltonian for fields), and a first treatment of general relativity. This is the bridge from particle mechanics to field theory — the same variational principles that govern particles now govern fields. Essential before QFT.
  - Emphasize: Ch 1-5 (SR and classical fields). Ch 10-14 (GR introduction) are enriching but will be done more carefully in Stage 4.

### Track B: Graduate Quantum Mechanics

- [ ] Modern Quantum Mechanics, by J. J. Sakurai and Jim Napolitano
  - The standard graduate QM text. Starts from the Dirac notation and state-space formalism — no wavefunction crutch from the start. Covers angular momentum algebra (SU(2) representations), perturbation theory, scattering, and the path integral. Requires functional analysis (Hilbert spaces, operators) and Lie groups (angular momentum = representation theory of su(2)). This book makes clear that QM is fundamentally about symmetry.
  - Emphasize: Ch 1-5 (formalism, harmonic oscillator, angular momentum) are the core. Ch 6-8 (perturbation theory, scattering) are essential for QFT.

### Track C: Statistical Mechanics

- [ ] Statistical Mechanics: An Introduction, by D. Bowley and M. Sanchez
  - Accessible undergraduate-level introduction: ensembles, partition functions, thermodynamic quantities. Sets the vocabulary before Pathria.
- [ ] Statistical Mechanics, by R. K. Pathria and Paul Beale
  - The graduate standard. Covers the three ensembles in depth, quantum statistical mechanics (Bose-Einstein, Fermi-Dirac distributions), phase transitions, and fluctuations. Required background for QFT (thermal field theory and finite-temperature methods appear in the Standard Model).
  - Emphasize: Ch 1-8 (classical and quantum statistical mechanics). Ch 9-13 (phase transitions) are important but can be deferred.

---

## Stage 4: General Relativity

Math prereqs: Math Stage 3 Track C complete — Do Carmo, Needham's *Visual Differential Geometry*, and Lee's *Introduction to Smooth Manifolds*. GR is applied differential geometry; without smooth manifolds, the tensor formalism is just symbol manipulation.

### Track A: Main Text

- [ ] Spacetime and Geometry: An Introduction to General Relativity, by Sean Carroll
  - The modern standard for learning GR. Carroll writes in the style of this list: every definition is motivated, every equation is derived, the geometry is front and center. Covers manifolds and tensors (self-contained review), curvature, the Einstein field equations, the Schwarzschild solution, black holes, and cosmology. The differential geometry chapter is excellent but will be much deeper after Lee.
  - Emphasize: Ch 1-4 (manifolds, curvature, Einstein equations). Ch 5-8 (solutions, black holes, cosmology) build directly on this. Ch 9 (linearized GR and gravitational waves) is increasingly important experimentally.

### Track B: Depth and Reference

- [ ] General Relativity, by Robert M. Wald
  - Mathematically rigorous — uses the abstract differential geometry formalism properly (no coordinate-centric shortcuts). Covers the same material as Carroll but proves more and hand-waves less. Ideal as a second pass after Carroll for the topics that Carroll motivates but doesn't fully prove. Essential for anyone who wants to do research in GR.
  - Emphasize: Ch 1-6 (the core of classical GR). Ch 7-9 (singularities, Penrose diagrams, black hole thermodynamics) go beyond Carroll.
- [ ] Gravitation, by Misner, Thorne, and Wheeler (MTW)
  - Encyclopedic (1300 pages), written in a unique two-track format distinguishing geometric insight from computation. Not meant to be read cover to cover — use as a deep reference alongside Carroll and Wald. Famous for its geometric way of thinking about tensors and curvature.
  - Approach: Read Carroll first. Then use MTW for topics where you want more derivation or a different geometric perspective. The "track 1" chapters are self-contained.

---

## Stage 5: Quantum Field Theory

Math prereqs: Math Stage 3 fully complete — especially functional analysis (S&S Vol. 4), Lie groups (Hall), complex analysis, and differential geometry. Physics prereqs: Stage 3 Track A (classical field theory) + Stage 3 Track B (graduate QM) + Stage 2 Track A (special relativity) must all be solid.

### Track A: Bridge and Orientation

- [ ] Quantum Field Theory in a Nutshell, by Anthony Zee
  - Conceptual overview of QFT: path integrals, Feynman diagrams, symmetry breaking, gauge invariance, and the Standard Model — all motivated and explained before the heavy formalism. This is not a replacement for Peskin & Schroeder; it is the book that makes Peskin & Schroeder readable by giving you the big picture first.
  - Read before Peskin. Return to Zee chapters after working through the corresponding Peskin material.
- [ ] Geometry, Topology and Physics, by Mikio Nakahara
  - A physics-oriented treatment of the mathematics needed for QFT and string theory: differential forms, fiber bundles, connections, characteristic classes, and homotopy groups. This is the bridge from Lee's smooth manifolds to gauge field theory, where connections on principal fiber bundles *are* the gauge fields. Read the relevant chapters as needed alongside QFT study.

### Track B: Main QFT Texts

- [ ] An Introduction to Quantum Field Theory, by Peskin and Schroeder
  - The standard graduate QFT textbook. Derives canonical quantization and the path integral formalism, Feynman rules, renormalization, QED, non-Abelian gauge theories, and spontaneous symmetry breaking. Dense but thorough — every physicist has read this book.
  - Emphasize: Part I (Ch 1-7: free fields, Feynman diagrams, QED). Part II (Ch 8-13: functional methods, renormalization) is where QFT gets deep. Part III (Ch 14-20: non-Abelian gauge theories, Standard Model) is the payoff.
- [ ] Quantum Field Theory and the Standard Model, by Matthew Schwartz
  - More modern than Peskin. Conceptually cleaner in many places, with better physical motivation. Covers the same core material and goes further into the Standard Model and effective field theories. Read alongside or after Peskin for a second perspective and to fill gaps.

---

## Stage 6: Advanced Topics

Physics prereqs: Stage 5 complete (full QFT). Math prereqs: Math Stage 3 Track D (algebraic topology: Hatcher) for string theory.

Different tracks can be read in parallel once Stage 5 is done.

### Track A: Particle Physics and the Standard Model

- [ ] Introduction to Elementary Particles, by David Griffiths
  - Accessible and concrete introduction to particle physics: the Standard Model, Feynman rules for all interactions, quark model, electroweak unification. Read early in Stage 6 — it is less technical than the QFT texts and gives the physical map before the formalism.
- [ ] Quarks and Leptons, by Halzen and Martin
  - More detailed and up-to-date than Griffiths. Derives the Standard Model interactions from gauge symmetry and covers hadron physics, QCD phenomenology, and electroweak theory. The standard undergraduate-to-graduate bridge for particle physics.
- [ ] The Quantum Theory of Fields (Vols. 1–3), by Steven Weinberg
  - The deepest and most careful treatment of QFT, written by one of its architects. Vol. 1: foundations, canonical quantization. Vol. 2: modern applications, the Standard Model. Vol. 3: supersymmetry. Weinberg derives QFT from first principles of Lorentz invariance and quantum mechanics — a completely different and more fundamental perspective than Peskin. Read after Peskin & Schwartz.

### Track B: Advanced General Relativity

- [ ] The Large Scale Structure of Space-Time, by Hawking and Ellis
  - The classic rigorous treatment of global GR: causal structure, singularity theorems, black holes, and cosmology. Requires Wald as background. This is the mathematical toolkit behind Penrose and Hawking's singularity theorems.
- [ ] Quantum Fields in Curved Space, by Birrell and Davies
  - The bridge between QFT and GR: how quantum field theory behaves in curved spacetime. Covers Hawking radiation, the Unruh effect, and particle creation in cosmology. Requires both Stage 4 (full GR) and Stage 5 (full QFT).

### Track C: String Theory

- [ ] A First Course in String Theory, by Barton Zwiebach
  - The most accessible serious introduction to string theory. Self-contained, pedagogical, and carefully motivated. Covers bosonic strings, superstrings, D-branes, and compactification without assuming QFT fluency at the level of Polchinski. Best starting point.
- [ ] String Theory (Vols. 1–2), by Joseph Polchinski
  - The standard graduate reference. Vol. 1: bosonic strings, conformal field theory, string scattering amplitudes. Vol. 2: superstrings, D-branes, dualities. Rigorous and complete. Read after Zwiebach.
- [ ] Superstring Theory (Vols. 1–2), by Green, Schwarz, and Witten
  - The original systematic treatment of superstring theory, written just after the first superstring revolution. More classical in approach than Polchinski. Useful as a complement for topics that Polchinski covers tersely.

---

## Optional Reading

### Classical Physics

- [ ] Classical Mechanics, by Goldstein, Poole, and Safko
  - The older graduate mechanics standard. More encyclopedic than Landau — useful as a reference for canonical transformations, Hamilton-Jacobi theory, and action-angle variables.
- [ ] The Classical Theory of Fields (relevant chapters), by Landau & Lifshitz, Vol. 2
  - If Carroll's GR chapter on SR feels thin, return to Landau Vol. 2 for the relativistic mechanics and fields material at the same elegant level as Vol. 1.

### Quantum Mechanics

- [ ] Quantum Mechanics (Vols. 1–2), by Cohen-Tannoudji, Diu, and Laloe
  - Encyclopedic and extremely careful. An excellent reference alongside Sakurai — where Sakurai is terse, Cohen-Tannoudji over-explains. Particularly good for the complements (additional problems and applications at the end of each chapter).
- [ ] Principles of Quantum Mechanics, by Dirac
  - The original axiomatic treatment by the creator of the bra-ket notation. Very short and elegant. A worthwhile companion read after Griffiths to see QM stated in its most general and clean form.

### Quantum Field Theory

- [ ] Gauge Theory of Elementary Particle Physics, by Cheng and Li
  - A physically motivated treatment of gauge theories: Yang-Mills theory, spontaneous symmetry breaking, the Higgs mechanism. Good companion to Peskin Parts II-III.
- [ ] Aspects of Symmetry, by Sidney Coleman
  - Legendary lecture notes by Coleman. Covers instantons, large-N expansions, and symmetry methods in QFT. Advanced but beautifully written.

### General Relativity

- [ ] Gravity: An Introduction to Einstein's General Relativity, by James Hartle
  - Physics-first approach: starts with observations (GPS, black holes, gravitational waves) before introducing the mathematics. Good parallel read alongside Carroll for those who want more physical motivation earlier.

### Mathematical Physics

- [ ] Methods of Mathematical Physics (Vols. 1–2), by Courant and Hilbert
  - Classical treatment of the mathematics underlying physics: PDEs, variational methods, spectral theory, integral equations. Not a physics book but deeply physical in motivation.
- [ ] Mathematics for Physics, by Stone and Goldbart
  - Modern, rigorous survey of the mathematical structures that appear in physics: differential geometry, topology, group theory, functional analysis — all presented with physical applications. Useful bridge reference throughout Stages 3-6.
