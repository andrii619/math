# Reading List

Prioritize books that emphasize deep intuitive understanding of topics, have plenty of discussions and examples, and also emphasise rigorous proofs.
Some examples of the style of books we are aiming for: "Real Analysis" by Jay Cummings, "Linear Algebra Done Right" by Axler, "Understanding Analysis" by Abbott.

Goals:

* Achieve mathematical maturity at the level of a math PhD — not just applying methods, but understanding deeply enough to create new mathematics.
* Get to a level of deep and intuitive understanding of why things work in areas of machine learning, control theory, digital signal processing.
* Avoid 'recipe' books that show methods but do not show proofs or why things work. For example, a lot of statistics and ML books are like this.
* Be able to create and prove own theories.

---

## Stage 1

Books within the same track are sequential. Different tracks can be read in parallel.

### Track A: Analysis

- [X] Proofs, Jay Cummings
  - Completed: Chapters 1-5
- [O] Real Analysis, Jay Cummings

### Track B: Linear Algebra

- [ ] Introduction to Linear Algebra, Strang
  - Emphasize: Ch 1-7 (core linear algebra). Ch 8-12 (applications, numerical methods) are useful but less critical since Trefethen & Bau covers numerical LA later.
- [ ] Linear Algebra Done Right, Axler
  - Read cover to cover. Every chapter builds on the last.
- [ ] Linear and Geometric Algebra, Macdonald
  - Emphasize: Part II (geometric algebra). Part I overlaps with Strang/Axler — skim for review. Geometric algebra explains *why* the inner product is defined the way it is: the inner and outer products arise naturally as the symmetric and antisymmetric parts of the geometric product, making the definitions feel inevitable rather than arbitrary.

### Track C: Foundations (short reads, parallel with A or B)

- [ ] Naive Set Theory, Halmos
  - Emphasize: Ch 1-18 (sets, relations, functions, cardinality). Ch 19-25 (ordinals, cardinal arithmetic, axiom of choice) — read for exposure but don't get stuck.
- [ ] Visual Group Theory
- [ ] How to Solve It, Polya
  - Short read. Builds proof instincts and mathematical thinking habits — how mathematicians approach problems they haven't seen before.
- [ ] Journey Through Genius: Great Theorems of Mathematics, by William Dunham

### Track D: Abstract Algebra

- [X] Algebra, by Michael Artin
- [ ] Abstract Algebra, Pinter
  - Refresher: Pinter is gentler than Artin. With CE graduate algebra feeling rusty after ~5 years, read this before Aluffi in Stage 2 to reactivate groups, rings, and field theory.
- [ ] Contemporary Abstract Algebra by Joseph Gallian

### After Tracks A + B:

- [ ] Vector Calculus, Linear Algebra, and Differential Forms: A Unified Approach, by Hubbard & Hubbard
  - Emphasize: Ch 1-4 (derivatives in R^n, inverse/implicit function theorems, integration). Ch 5-6 (differential forms, manifolds) can be deferred — Needham and Lee cover this more deeply later.

---

## Stage 2

Books within the same track are sequential. Different tracks can be read in parallel.

### Track A: Real Analysis and Measure Theory

- [ ] Analysis I and II, Terrence Tao
  - Analysis I: Skim — construction of reals is unique to Tao, but most material overlaps with Cummings. Focus on later chapters.
  - Analysis II: Read carefully — metric spaces, Lebesgue integration, multivariable differential calculus are new and critical.
- [ ] Measures, Integrals, and Martingales, by Rene Schilling
  - Read cover to cover. This is the rigorous measure theory foundation for Durrett, Vershynin, and Evans.
  - Companion: "Counterexamples in Measure and Integration" by Schilling — use as a reference alongside each chapter, not sequentially.
- [ ] Fourier Analysis: An Introduction, by Stein and Shakarchi (Princeton Lectures in Analysis, Vol 1)
  - Emphasize: Ch 1-6 (Fourier series, Fourier transform, applications). Ch 7-8 are less critical.
  - Note: This is Vol 1 of a 4-volume series (see Vols 2-4 in Stages 2-3). The series forms a unified, motivated analysis curriculum.

### Track B: Complex Analysis (after Track A: Fourier; Needham first)

- [ ] Visual Complex Analysis, Tristan Needham
  - Read before or alongside Stein & Shakarchi Vol 2. Provides deep geometric intuition — complex maps, Möbius transformations, conformal mappings, contour integration — without which the formal theory feels unmotivated.
  - Emphasize: Ch 1-8. Ch 9-12 are more specialized.
- [ ] Complex Analysis, by Stein and Shakarchi (Princeton Lectures in Analysis, Vol 2)
  - The rigorous complement to Needham. Together they cover complex analysis from every angle: Needham gives geometry, Stein & Shakarchi gives proof. Covers Cauchy's theorem, residues, analytic continuation, entire functions, Riemann mapping theorem.

### Track C: Algebra (after Stage 1 Track D: Pinter refresher)

- [ ] Algebra: Chapter 0, by Paolo Aluffi
  - The modern, motivated treatment. Uses category theory as a unifying language from the start, showing *why* algebraic structures are defined the way they are. Covers groups, rings, modules, fields, and Galois theory. Replaces Pinter as the depth text — Pinter was for reactivation, this is for deep understanding.

### Track D: Topology (required — not a parallel side read)

- [ ] Topology, by Munkres
  - Emphasize: Part I fully (Ch 1-8: topological spaces, connectedness, compactness, metric spaces, separation axioms). This is a prerequisite for functional analysis, differential geometry, and algebraic topology.
  - Part II (algebraic topology) is covered more deeply by Hatcher in Stage 3 — can skim or skip here.

### Track E: Differential Equations and Dynamical Systems

- [ ] Ordinary Differential Equations, by V.I. Arnold
  - Emphasize: Ch 1-4 (phase spaces, vector fields, linear systems, stability). Ch 5-6 (oscillations, symmetry) are enriching but less essential.
- [ ] Nonlinear Dynamics and Chaos, by Steven Strogatz
  - Emphasize: Ch 1-9 (bifurcations, phase plane, limit cycles, Lorenz system). Ch 10-12 (fractals, strange attractors) are fascinating but less directly applicable.
- [ ] Partial Differential Equations: An Introduction, by Walter Strauss
  - The natural next step after ODEs and Fourier analysis. Covers the three classical PDEs — heat equation, wave equation, Laplace equation — which were Fourier's original motivation. The heat equation is literally *why* Fourier series were invented. Read after Stein & Shakarchi Vol 1. Accessible and concept-driven. Prepares for Evans in Stage 3.

### Track F: Probability (after Track A: Schilling)

- [ ] Probability, Durrett
  - Full measure-theoretic treatment. Read after Schilling.

### Track G: Category Theory (short parallel read — any time in Stage 2)

- [ ] Basic Category Theory, by Tom Leinster (free PDF)
  - ~200 pages. Introduces categories, functors, natural transformations, and universal properties. This is the language of modern pure mathematics — it makes Aluffi's algebra, Hatcher's algebraic topology, and Lee's geometry all feel more unified. Can be read alongside any other Stage 2 track.

### Track H: Applied (parallel with any track)

- [ ] Numerical Linear Algebra, by Trefethen & Bau
- [ ] Convex Optimization, by Boyd
  - Emphasize: Ch 1-5 (convex sets, functions, optimization problems, duality). Ch 6-11 (algorithms, applications) are useful but more computational.

---

## Stage 3

Different tracks can be read in parallel.

### Track A: Analysis Continued (after Stage 2 Track A: Schilling)

- [ ] Real Analysis, by Stein and Shakarchi (Princeton Lectures in Analysis, Vol 3)
  - Extends Schilling into territory needed for PDEs: L^p spaces, distributions, Sobolev spaces, and the Fourier transform in higher dimensions. Required before Evans. Read after Schilling.

### Track B: Functional Analysis (after Stage 2 Track D: Munkres)

- [ ] Introductory Functional Analysis with Applications, by Kreyszig
  - Gentle, motivated entry into functional analysis: normed spaces, Banach spaces, Hilbert spaces, spectral theory. Requires Munkres (topology) as background.
- [ ] Functional Analysis, by Stein and Shakarchi (Princeton Lectures in Analysis, Vol 4)
  - Natural continuation of the series. Covers distributions, Sobolev spaces, spectral theory of compact operators, and a chapter on Brownian motion — connecting back to probability. Read after Kreyszig.

### Track C: Differential Geometry (after Stage 2 Track D: Munkres + Hubbard & Hubbard)

- [ ] Differential Geometry of Curves and Surfaces, by Do Carmo
  - Classical, concrete differential geometry in R^2 and R^3: curves, surfaces, curvature, geodesics. Not abstract — this is the geometric intuition that makes manifold theory feel natural rather than arbitrary. Read this first.
- [ ] Visual Differential Geometry and Forms, by Tristan Needham
  - Deep geometric intuition for curvature, parallel transport, and Gauss-Bonnet. Best read alongside or after Do Carmo.
- [ ] Introduction to Smooth Manifolds, by John M. Lee
  - The modern rigorous standard for graduate differential geometry. Very well-motivated — Lee explains the *why* at each step. Covers smooth manifolds, tangent bundles, differential forms, integration on manifolds, Stokes' theorem in full generality. Requires Munkres (topology) and Hubbard & Hubbard (multivariable calculus).
- [ ] Introduction to Riemannian Manifolds, by John M. Lee
  - The direct sequel to Smooth Manifolds. Adds the metric structure: Riemannian metrics, connections, geodesics, the Riemann curvature tensor, sectional curvature, and the Jacobi equation. This is the geometry of curved spaces — the mathematical language that GR is written in. Without it, Carroll's GR is manageable but Wald is noticeably harder. Read after Lee's Smooth Manifolds.

### Track G: Lie Theory (after Stage 2 Track C: Aluffi + Stage 2 Track D: Munkres)

- [ ] Lie Groups, Lie Algebras, and Representations, by Brian Hall
  - The clearest rigorous treatment of Lie theory for a mathematical audience. Covers matrix Lie groups (GL, SL, SO, SU, Sp), the exponential map, Lie algebras, and the representation theory of SU(2), SU(3), and the Lorentz group. Hall builds intuition carefully — the exponential map is introduced geometrically before any formalism. This is an essential prerequisite for physics at the graduate level: angular momentum in QM is the representation theory of su(2); gauge theories in QFT are based on Lie group symmetries (U(1), SU(2), SU(3)); and the Lorentz group governs the entire structure of special and general relativity.
  - Emphasize: Ch 1-5 (matrix Lie groups and the exponential map), Ch 6-10 (representations of SU(2), SU(3), and the Lorentz group). Ch 11-16 go deeper into general semisimple theory — important for the Standard Model (SU(3) × SU(2) × U(1)) but can be read alongside physics Stage 5 rather than as a prerequisite.

### Track D: Algebraic Topology (after Stage 2 Track D: Munkres)

- [ ] Introduction to Topological Manifolds, by John M. Lee
  - Bridge between Munkres and Hatcher. Covers manifold topology, fundamental groups, covering spaces in the same readable, motivated style as Lee's smooth manifolds book.
- [ ] Algebraic Topology, by Hatcher
  - The standard graduate text. Covers fundamental groups, homology, and cohomology. Free online. Requires Munkres (Part I) as background.

### Track E: Partial Differential Equations (after Track A: S&S Vol 3 + Track B: Kreyszig)

- [ ] Partial Differential Equations, by Lawrence C. Evans
  - The standard graduate PDE text. Requires functional analysis (Sobolev spaces from S&S Vol 3, operator theory from Kreyszig). Heavy, but the most rigorous and complete treatment. This is where Fourier's original insights live in their full mathematical form.

### Track F: Probability (after Stage 2 Track F: Durrett)

- [ ] High-Dimensional Probability: An Introduction with Applications in Data Science, by Roman Vershynin
- [ ] Stochastic Differential Equations, by Oksendal
  - Also requires Track B: Kreyszig (functional analysis).

---

## Stage 5 (Optional — Pure Math Depth)

This stage deepens the pure math foundation into areas that are not required for ML, control, or DSP but are essential for algebraic geometry and for understanding QFT and string theory at a research level. All tracks require Stage 3 to be complete. Different tracks can be read in parallel.

### Track A: Commutative Algebra (after Stage 2 Track C: Aluffi)

- [ ] Introduction to Commutative Algebra, by Atiyah and Macdonald
  - ~130 pages. Covers rings, modules, localization, Noetherian rings, primary decomposition, and Krull dimension. The standard concise treatment — every theorem is precisely stated and proved. Required before Hartshorne and before serious algebraic geometry. Also useful for homological algebra.

### Track B: Homological Algebra (after Track A + Stage 3 Track D: Hatcher)

- [ ] An Introduction to Homological Algebra, by Charles Weibel
  - The standard graduate reference. Covers chain complexes, derived functors (Ext and Tor), spectral sequences, and sheaf cohomology. Homological algebra is the connective tissue between algebra and topology — it underlies Hatcher's homology theory and is essential for algebraic geometry (sheaves, cohomology of schemes). In physics: BRST cohomology (the formalism for gauge fixing in QFT and the definition of physical states in string theory) is directly an application of this machinery.
  - Emphasize: Ch 1-3 (chain complexes, derived functors). Ch 5 (spectral sequences) are important but can be deferred to when they're needed in context.

### Track C: Riemann Surfaces (after Stage 2 Track B: Complex Analysis + Stage 3 Track C: Lee Smooth Manifolds)

- [ ] Riemann Surfaces, by Simon Donaldson
  - Short (~180 pages), beautifully motivated, and rigorous. Covers the definition of Riemann surfaces, meromorphic functions, the Riemann-Roch theorem, and the uniformization theorem. Donaldson writes in the style of this list — he explains the *why* at every step. The physics payoff is direct: the string worldsheet is a Riemann surface, string scattering amplitudes are integrals over moduli spaces of Riemann surfaces, and conformal field theory is naturally formulated on them.
- [ ] Algebraic Curves and Riemann Surfaces, by Rick Miranda
  - More comprehensive than Donaldson. Develops Riemann surfaces from both the analytic and algebraic perspectives simultaneously, building toward sheaf theory and the algebraic geometry connection. Read after Donaldson if you want the full bridge to Hartshorne.

### Unlocked after Stage 5

The "Other" section entry — Hartshorne's *Algebraic Geometry* — becomes accessible after completing all three tracks here. Algebraic geometry is relevant for string theory compactifications (Calabi-Yau manifolds, mirror symmetry) and is a deep area of pure mathematics in its own right.

---

## Stage 4

Pure math foundation complete — this stage applies it to the target domains. Different tracks can be read in parallel.

### Track A: Control (after Stage 2 Track E + Stage 3 Track B)

- [ ] Signals and Systems, by Oppenheim & Willsky
  - Shared prerequisite with Track B. Conceptual foundation for LTI systems, convolution, Fourier/Laplace/Z transforms, and sampling.
- [ ] Feedback Systems: An Introduction for Scientists and Engineers, by Karl Johan Astrom and Richard Murray
- [ ] Linear System Theory and Design, by Chen
  - Rigorous and concept-driven. Covers state-space, controllability, observability, stability. Essential bridge before Liberzon.
- [ ] Calculus of Variations and Optimal Control Theory, by Daniel Liberzon

### Track B: Digital Signal Processing (after Stage 2 Track A: Fourier)

- [ ] Signals and Systems, by Oppenheim & Willsky (shared with Track A)
- [ ] Understanding Digital Signal Processing, by Richard Lyons
- [ ] A Wavelet Tour of Signal Processing, by Mallat
  - Idea-driven and narrative. Builds a deep mental model of time-frequency analysis and wavelets; also connects to ML.

### Track C: Machine Learning Theory (after Stage 3 Track F: Vershynin)

- [ ] Understanding Machine Learning, by Shalev-Shwartz & Ben-David
  - One of the most explanatory ML theory texts: PAC learning, VC dimension, Rademacher complexity — all with motivated proofs.

### Track D: Robotics

- [ ] Robotics, Vision and Control, by Peter Corke
- [ ] Probabilistic Robotics, by Sebastian Thrun, Wolfram Burgard, and Dieter Fox
- [ ] State Estimation for Robotics, by Timothy Barfoot
- [ ] Planning Algorithms, by Steven LaValle

### Track E: Information Theory

- [ ] Information Theory, Inference, and Learning Algorithms, by MacKay

### Track F: Capstone (parallel with any track)

- [ ] Data-Driven Science and Engineering: Machine Learning, Dynamical Systems, and Control, by Brunton & Kutz

---

## Optional Reading

### Proofs

- [ ] How to Prove It, Velleman

### Analysis

- [ ] Understanding Analysis, Abbott
- [ ] The Cauchy-Schwarz Master Class, by J. Michael Steele
  - Develops the art of proving and applying inequalities: Cauchy-Schwarz, AM-GM, Jensen, Chebyshev, and more. Not a prerequisite for anything specific, but builds the kind of estimation intuition that appears constantly in analysis, probability, and ML theory. Well-written and proof-driven.

### Group Theory

- [ ] Group Theory and Quantum Mechanics, by Michael Tinkham
  - The classic bridge from abstract representation theory to concrete QM applications: molecular symmetry, crystal field theory, angular momentum, selection rules, and the classification of particles by irreducible representations. Hall (Stage 3 Track G) gives the rigorous math foundation; Tinkham shows how physicists actually use it. Read alongside or after Sakurai.

### Algebra

- [ ] Galois Theory, by Ian Stewart
  - Short, readable standalone treatment of Galois theory. Good if you want a dedicated narrative alongside Aluffi's coverage.

### Category Theory

- [ ] Category Theory in Context, by Emily Riehl (free PDF)
  - Deeper follow-up to Leinster. Covers adjunctions, limits, and monads in full. Read after Leinster if you want to go further.

### Functional Analysis

- [ ] Introductory Real Analysis, by Kolmogorov & Fomin

### Probability

- [ ] Introduction to Probability, by Blitzstein & Hwang
- [ ] First Look At Rigorous Probability Theory, Rosenthal

### Linear Algebra

- [ ] Introduction to Linear and Matrix Algebra, by Nathaniel Johnston
- [ ] Advanced Linear and Matrix Algebra, by Nathaniel Johnston

### Statistics

- [ ] Statistical Inference, by Casella & Berger
  - Classical point estimation, hypothesis testing, and confidence intervals. Useful reference but not on the critical path.

### Number Theory

- [ ] An Introduction to the Theory of Numbers, by Hardy & Wright
  - Euler and Fermat were fundamentally number theorists. A beautifully written classical text. Not required but adds important depth given those inspirations.

### Digital Signal Processing

- [ ] Kalman Filter from the Ground Up, by Alex Becker

### Control

- [ ] Feedback Control of Dynamic Systems, by Franklin and Powell

---

## Other

- [ ] Introduction to Commutative Algebra, by Atiyah and Macdonald
  - Required before Hartshorne. ~130 pages. Covers rings, modules, localization, Noetherian rings, and dimension theory — the algebraic machinery that algebraic geometry runs on. Without this, Hartshorne is essentially unreadable.
- [ ] Algebraic Geometry, by Hartshorne
  - Prereq: Atiyah-Macdonald (commutative algebra) + Aluffi (algebra) + Hatcher (algebraic topology). Relevant for string theory (Calabi-Yau compactifications, mirror symmetry) but a deep commitment — not on the critical path for any other goal.
