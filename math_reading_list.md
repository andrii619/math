# Reading List

Prioritize books that emphasize deep intuitive understanding of topics, have plenty of discussions and examples, and also emphasise rigorous proofs.
Some examples of the style of books we are aiming for: "Real Analysis" by Jay Cummings, "Linear Algebra Done Right" by Axler, "Understanding Analysis" by Abbott.

Goals:

* Achieve mathematical maturity at PhD level — breadth of qualifying exams plus depth to do research
* Get to a level of deep and intuitive understanding of why things work in machine learning, control theory, digital signal processing
* Avoid 'recipe' books that show methods but do not show proofs or why things work
* Be able to create and prove own theories

## Stage 1: Foundations

Books within the same track (A, B, C) are sequential. Different tracks can be read in parallel.

### Track A: Analysis

- [X] Proofs, Jay Cummings
- [O] Real Analysis, Jay Cummings

### Track B: Linear Algebra

**Reading approach:** Once a few chapters into Axler, start the Stage 2 abstract algebra intro (Pinter or Gallian) in parallel. Linear algebra and abstract algebra reinforce each other — examples from each illuminate the other, and Axler's structural treatment of vector spaces lands better with parallel exposure to general algebraic structures. See Stage 2 Track C for the algebra intro.

- [ ] Computational/concrete linear algebra (optional — pick one if you want this layer, or skip):
  - *Introduction to Linear Algebra*, Strang — geometric intuition, applications-driven, famous "four fundamental subspaces" picture. Light on proofs. Engineering/applications flavor.
  - *Introduction to Linear and Matrix Algebra*, Nathaniel Johnston — more rigorous and proof-aware than Strang, modern pedagogy, cleaner exposition. More math-major flavor.
  - Sample both and pick the one whose style clicks. Skip entirely if comfortable with matrices and vectors from prior exposure — Axler is sufficient for the rigorous foundation.
  - Strang emphasis: Ch 1-7. Ch 8-12 less critical (Trefethen & Bau covers numerical LA).
- [ ] Linear Algebra Done Right, Axler
  - Read cover to cover. Every chapter builds on the last.
  - Treats linear algebra as a chapter of abstract algebra rather than as matrix manipulation. Axler deliberately delays determinants, treats vector spaces axiomatically, focuses on linear maps as primary objects.
- [ ] Linear and Geometric Algebra, Macdonald
  - Emphasize: **Part II only** (geometric algebra). Part I overlaps with Strang/Axler — skip.

### Track C: Foundations (short reads, parallel with A or B)

- [ ] A Book of Set Theory, Pinter
  - Pedagogically closer to the Cummings/Axler/Abbott style than Halmos. Many exercises, intuitive explanations.
  - Emphasize: first ~2/3 (sets, relations, functions, cardinality, ordinals, axiom of choice). Later axiomatic/independence material is for interest — don't get stuck.
  - Alternative: Halmos, *Naive Set Theory* — shorter and more elegant but terse and not pedagogical; better as review than as first exposure.
- [ ] Visual Group Theory, Carter
- [ ] How to Solve It, Polya
  - Short read. Builds proof instincts and mathematical thinking habits.
- [ ] A Walk Through Combinatorics, Miklós Bóna
  - Pedagogical undergrad combinatorics text. Lots of examples. Can be read any time after basic proof comfort.

### Track D: Logic (NEW; parallel with A, B, or C)

- [ ] A Mathematical Introduction to Logic, Herbert Enderton
  - Standard upper-undergrad/early-grad logic text. Propositional and first-order logic, completeness, compactness, undecidability.
- [ ] An Introduction to Gödel's Theorems, Peter Smith
  - Focused entirely on the incompleteness theorems. Pedagogical and matches your style preference. Read after or alongside Enderton.

### After Tracks A + B:

- [ ] Vector Calculus, Linear Algebra, and Differential Forms: A Unified Approach, Hubbard & Hubbard
  - Emphasize: Ch 1-4 (derivatives in R^n, inverse/implicit function theorems, integration). Ch 5-6 (differential forms, manifolds) can be deferred — Needham covers this more intuitively later.

---

## Stage 2: Core Graduate Material

Books within the same track are sequential. Different tracks can be read in parallel.

### Track A: Analysis

- [ ] Analysis I and II, Terence Tao
  - Analysis I: Skim chapters on construction of reals, focus on later chapters building on Cummings.
  - Analysis II: Read carefully — metric spaces, Lebesgue integration, multivariable differential calculus. Skim multivariable chapters since Hubbard covers this.
- [ ] Measures, Integrals, and Martingales, René Schilling
  - Read cover to cover. Measure theory foundation for Folland, Durrett, and Vershynin.
  - Companion: "Counterexamples in Measure and Integration" by Schilling. Use as a reference alongside each chapter.
- [ ] Fourier Analysis: An Introduction, Stein & Shakarchi
  - Emphasize: Ch 1-6 (Fourier series, Fourier transform, applications). Ch 7-8 are less critical for DSP/ML.
- [ ] Visual Complex Analysis, Tristan Needham
  - Emphasize: Ch 1-8 (geometry of complex maps, Mobius transformations, conformal mappings, contour integration). Ch 9-12 are more specialized.

### Track B: Topology (NEW — promoted from optional)

- [ ] Topology, Jänich
  - Short (~200 pages), geometric and intuitive. Read first or in parallel with Munkres for motivation and feel. Style is informal — some readers love it, others find it too hand-wavy. Sample before committing.
- [ ] Topology, Munkres
  - Part I only (Ch 1-8): topological spaces, connectedness, compactness, metric spaces, countability/separation axioms.
  - Rigorous and complete with excellent exercises. Less intuition-forward than Cummings/Abbott style, but the standard for a reason.
  - Prerequisite for functional analysis, differential geometry, and abstract measure theory. **Do not skip.**

### Track C: Algebra (EXPANDED)

**Reading approach:** Start the abstract algebra intro (Pinter or Gallian) in parallel with Axler in Stage 1, once you're a few chapters into Axler. The two reinforce each other. Continue with Aluffi after both Axler and the chosen intro are well-developed.

- [ ] Intro to Abstract Algebra (pick one — sample both to decide):
  - *A Book of Abstract Algebra*, Pinter — shorter (~400 pages), efficient, elegant. Stylistically consistent with Pinter's set theory.
  - *Contemporary Abstract Algebra*, Gallian — longer (~600 pages), more thorough, example-heavy with applications and biographical context. More traditional textbook experience.
  - Both cover groups, rings, fields, and introductory Galois theory at roughly the same level. Pick based on preferred pace and style.
- [ ] Algebra: Chapter 0, Paolo Aluffi
  - The main algebra text. Categorical flavor, intuitive exposition, rigorous. Covers groups, rings, modules, fields, Galois theory, homological algebra.
  - Reference alternative: Dummit & Foote (more comprehensive, less elegant).
- [ ] Introduction to Commutative Algebra, Atiyah & Macdonald
  - **Read only after completing Aluffi.** A&M requires comfort with modules, localizations, and tensor products that Aluffi builds — starting it earlier will feel unmotivated. ~130 pages, dense and brilliant. Standard prerequisite for Hartshorne's algebraic geometry and for Weibel's homological algebra (Stage 5). Do not move this above Aluffi.
  - Alternative for fuller treatment: Eisenbud, *Commutative Algebra with a View Toward Algebraic Geometry* — longer, more pedagogical, better for self-study.

### Track D: Combinatorics (NEW; after Stage 1 Track C: Bóna)

- [ ] Enumerative Combinatorics, Vol. 1, Richard Stanley
  - Graduate combinatorics standard. Dense but canonical. Generating functions, partitions, bijective proofs.
- [ ] Graph Theory, Reinhard Diestel (free online)
  - Graduate graph theory text. More accessible than Bollobás. Covers connectivity, matching, planarity, coloring, extremal graph theory.
- [ ] Spielman lecture notes on Spectral Graph Theory (free online, Yale)
  - Connects graph theory to linear algebra. Directly relevant to graph neural networks and spectral methods in ML.
  - Optional advanced extension: Flajolet & Sedgewick, *Analytic Combinatorics* (free online) — connects combinatorics to complex analysis via generating functions.

### Track E: Differential Equations and Dynamical Systems

- [ ] Ordinary Differential Equations, V.I. Arnold
  - Emphasize: Ch 1-4 (phase spaces, vector fields, linear systems, stability). Ch 5-6 are enriching but less essential.
- [ ] Nonlinear Dynamics and Chaos, Steven Strogatz
  - Emphasize: Ch 1-9 (bifurcations, phase plane, limit cycles, Lorenz system). Ch 10-12 are fascinating but less directly applicable.

### Track F: Probability (after Track A: Schilling)

- [ ] Probability with Martingales, David Williams
  - Read first. Shorter and more intuitive than Durrett, excellent on martingales.
- [ ] Probability: Theory and Examples, Durrett
  - Read second for breadth and as research reference.

### Track G: Applied (parallel with any track)

- [ ] Numerical Linear Algebra, Trefethen & Bau
- [ ] Convex Optimization, Boyd & Vandenberghe
  - Emphasize: Ch 1-5 (convex sets, functions, optimization problems, duality). Ch 6-11 are useful but more applied.
- [ ] Statistical Inference, Casella & Berger
  - Foundation only. Supplement with van der Vaart in Stage 3.

---

## Stage 3: Advanced Foundations

Different tracks can be read in parallel.

### Track A: Graduate Real Analysis (NEW)

- [ ] Real Analysis: Modern Techniques and Their Applications, Gerald Folland
  - The qual-exam standard. Unifies measure theory, functional analysis, Fourier, and distributions at graduate level.
  - Essential bridge between Schilling and research-level work.

### Track B: Functional Analysis (after Stage 2 Track B: Topology, Stage 3 Track A: Folland)

- [ ] Introductory Functional Analysis with Applications, Kreyszig

### Track C: Probability & Statistics (after Stage 2 Track F)

- [ ] High-Dimensional Probability: An Introduction with Applications in Data Science, Roman Vershynin
- [ ] Asymptotic Statistics, A.W. van der Vaart
  - Modern theoretical statistics: empirical processes, M-estimators, semiparametric theory. Essential for ML theory.

### Track C2: Stochastic Calculus (after Track B: Kreyszig; parallel with Track C)

Stochastic calculus is foundational for modern ML theory (SGD-as-SDE, diffusion models, score-based generative models, neural SDEs), stochastic control, and filtering. One introductory text is not enough for PhD-level depth.

- [ ] Stochastic Differential Equations, Øksendal
  - Readable introduction. Itô calculus, SDEs, diffusions, applications to filtering and optimal control. Glosses over measure-theoretic heavy lifting.
- [ ] Brownian Motion, Martingales, and Stochastic Calculus, Jean-François Le Gall
  - Rigorous treatment. Cleaner and more modern than Karatzas & Shreve; better fit for the intuitive-but-rigorous style.
  - Alternative: Karatzas & Shreve, "Brownian Motion and Stochastic Calculus" — denser, more comprehensive, standard reference.
- [ ] Applied Stochastic Differential Equations, Särkkä & Solin (optional, free online)
  - Bridges theory to filtering, ML, and signal processing applications. Complement, not replacement.

### Track D: Category Theory (NEW — short read, parallel with anything)

- [ ] Basic Category Theory, Tom Leinster
  - ~180 pages, free online. Small investment, huge downstream payoff in algebra, topology, and modern ML theory.

### Track E: Geometry

**Do not trim this track.** It has four sequential layers, each serving a distinct purpose. Removing any one leaves a gap: Do Carmo provides the concrete geometric intuition; Needham bridges classical surfaces to modern forms language; Lee Smooth Manifolds provides the rigorous abstract theory; Lee Riemannian Manifolds adds the metric structure required for GR. The physics track (Carroll → Wald) depends on this entire sequence.

- [ ] Differential Geometry of Curves and Surfaces, Manfredo Do Carmo
  - Classical, concrete differential geometry in R² and R³: curves, surfaces, curvature, geodesics, Gauss-Bonnet. **Do not skip.** Going straight to Lee's Smooth Manifolds without Do Carmo means learning the abstract machinery without any feel for what curvature actually is. The abstraction in Lee only lands naturally after you've seen curvature concretely. Read this first.
- [ ] Visual Differential Geometry and Forms, Tristan Needham
  - Deep geometric intuition for curvature, parallel transport, and differential forms. Bridges the language of classical surfaces (Do Carmo) to the differential forms formalism Lee uses. Best read alongside or immediately after Do Carmo.
- [ ] Introduction to Smooth Manifolds, John M. Lee
  - The modern rigorous standard. Covers smooth manifolds, tangent bundles, differential forms, integration on manifolds, Stokes' theorem in full generality. Essential for geometric control theory, information geometry, and all differential topology downstream.
- [ ] Introduction to Riemannian Manifolds, John M. Lee
  - **Required for the physics track.** Adds the metric structure to smooth manifolds: Riemannian metrics, connections, geodesics, the Riemann curvature tensor, sectional curvature, Jacobi fields. GR is pseudo-Riemannian geometry — this is the mathematical language it is written in. Carroll's GR book teaches some of this itself, but Wald's rigorous treatment assumes you already have it. Without this book the jump to Wald is noticeably hard. Read directly after Lee's Smooth Manifolds.

### Track F: PDEs

**Do not start with Evans directly.** Evans is a graduate reference that assumes prior familiarity with the three classical PDEs and gives no physical warmup. Strauss provides the essential concrete foundation first.

- [ ] Partial Differential Equations: An Introduction, Walter Strauss
  - Accessible and concept-driven. Covers the heat equation, wave equation, and Laplace equation with physical motivation and worked solutions. Short and readable. **Required before Evans**: Evans abstracts everything into functional-analytic language immediately. Without Strauss, Evans feels unmotivated and the physical meaning of the equations is invisible. The heat equation is also historically why Fourier series were invented — Strauss makes this clear.
- [ ] Partial Differential Equations, Lawrence C. Evans
  - The standard graduate text. Requires functional analysis (Sobolev spaces, operator theory from Track B: Kreyszig). The most rigorous and complete treatment available. Read after both Strauss and Kreyszig.

### Track G: Optimal Transport (NEW; after Track A: Folland and Track B: Kreyszig)

Central to modern ML theory (Wasserstein GANs, flow matching, diffusion via Schrödinger bridges), distribution shift, and gradient flows in probability space.

- [ ] Computational Optimal Transport, Peyré & Cuturi (free online)
  - Applied entry point. Sinkhorn, Wasserstein distances, applications.
- [ ] Optimal Transport for Applied Mathematicians, Filippo Santambrogio
  - Rigorous middle ground. More accessible than Villani.
- [ ] Optimal Transport: Old and New, Villani (reference only)
  - Comprehensive, 1000 pages. Use as reference, not read-through.

### Track H: Lie Groups & Mathematical Physics Bridge (NEW; for physics track)

Required if pursuing the physics reading list. Also useful standalone for geometric ML and representation theory in general.

- [ ] Lie Groups, Lie Algebras, and Representations, Brian C. Hall
  - Intuitive but rigorous. Bridge to QM and particle physics. Read after basic group theory and functional analysis.
- [ ] Representation Theory: A First Course, Fulton & Harris
  - Standard reference for representation theory of finite groups and Lie groups. Direct relevance to physics (particle physics, QFT) and to algebraic combinatorics. Read after Hall.
  - Free alternative: Etingof et al., *Introduction to Representation Theory* (MIT lecture notes online) — more concise.
- [ ] Mathematical Methods of Classical Mechanics, V.I. Arnold
  - Symplectic geometry reformulation of classical mechanics. Essential bridge between differential geometry and physics.

---

## Stage 4: Applied Domains

Pure math first — this stage applies the foundation to target domains. Different tracks can be read in parallel.

### Track A: Control (after Stage 2 Track D + Stage 3 Tracks B, E, F)

- [ ] Linear System Theory and Design, Chen
  - Rigorous and concept-driven. State-space, controllability, observability, stability.
- [ ] Calculus of Variations and Optimal Control Theory, Daniel Liberzon
- [ ] Continuous-time Stochastic Control and Optimization with Financial Applications, Huyên Pham (optional, after Stage 3 Track C2)
  - Stochastic optimal control, HJB equations. Only if stochastic control is a target area.

### Track B: Digital Signal Processing (after Stage 2 Track A: Fourier)

- [ ] Discrete-Time Signal Processing, Oppenheim & Schafer
  - Replaces Oppenheim & Willsky — more rigorous treatment of LTI systems, convolution, transforms, sampling.
- [ ] A Wavelet Tour of Signal Processing, Mallat
  - Idea-driven and narrative. Deep mental model of time-frequency analysis and wavelets; connects to ML.

### Track C: Machine Learning Theory (after Stage 3 Track C)

- [ ] Understanding Machine Learning, Shalev-Shwartz & Ben-David
  - PAC learning, VC dimension, Rademacher complexity — all with motivated proofs.

### Track D: Capstone (parallel with any track)

- [ ] Information Theory, Inference, and Learning Algorithms, MacKay
- [ ] Data-Driven Science and Engineering: Machine Learning, Dynamical Systems, and Control, Brunton & Kutz

---

## Stage 5: Pure Math Depth (Optional)

This stage is not on the critical path for ML, control, DSP, or classical physics. It is the prerequisite for algebraic geometry (Hartshorne) and for understanding QFT and string theory at a structural level — specifically BRST cohomology (gauge fixing in QFT and string theory's physical state space) and the Riemann surface geometry of the string worldsheet.

Prerequisites: Stage 2 Track C (Aluffi + Atiyah-Macdonald) + Stage 3 Track D (Hatcher, algebraic topology).

### Track A: Homological Algebra (after Stage 2 Track C: Atiyah-Macdonald + Stage 3 Track D: Hatcher)

**Do not remove or merge this track.** Homological algebra is the connective tissue between algebra and topology, and is a hard prerequisite for Hartshorne. In physics, BRST cohomology — the formalism that defines gauge-fixed path integrals in QFT and the physical Hilbert space of string theory — is a direct application of derived functors. Without this, those physics arguments are opaque symbol manipulation.

- [ ] An Introduction to Homological Algebra, Charles Weibel
  - The standard graduate text. Covers chain complexes, derived functors (Ext and Tor), spectral sequences, and sheaf cohomology. Requires Atiyah-Macdonald (for the commutative algebra) and Hatcher (for the topological motivation — homology is what derived functors compute). Emphasize: Ch 1–3 (chain complexes, projective/injective resolutions, derived functors). Ch 5 (spectral sequences) on-demand, when needed in context.
  - Gentler alternative: Rotman, *An Introduction to Homological Algebra* (2nd ed.) — more examples and motivation, better for self-study; use if Weibel feels too terse to start.

### Unlocked after Stage 5

Completing Track A (together with Atiyah-Macdonald from Stage 2 and Hatcher from Stage 3) makes Hartshorne's *Algebraic Geometry* (see companion list entry) accessible. Algebraic geometry is relevant for string theory compactifications (Calabi-Yau manifolds, mirror symmetry) and is a deep area of pure mathematics in its own right.

---

## Optional / Supplementary Reading

### History and Foundations

These books cover the origins of mathematical concepts — how π, e, calculus, group theory, and other ideas came to be, and what problems they solved. Valuable for building mathematical culture and intuition alongside the technical study. No prerequisites; can be read any time as "rest reading" between more demanding texts.

**Primary recommendations:**

- [ ] *The History of Mathematics*, Jay Cummings
  - Same long-form, conversational, intuition-rich style as Cummings' *Proofs* and *Real Analysis*. Given you already like his style, this is the best starting point.
- [ ] Mathematics and Its History, John Stillwell
  - More systematic and academic than Cummings. Good second book for deeper coverage of how subjects evolved and connected across eras.
- [ ] Journey Through Genius: The Great Theorems of Mathematics, William Dunham
  - Deep-dive chapters on landmark theorems (Euclid on primes, Archimedes on circle area, Cardano on cubics, Euler on e and the Basel problem, Cantor on cardinalities). Presents proofs as the original mathematicians wrote them. Very readable.

**Topic-specific deep dives (all optional):**

- [ ] *e: The Story of a Number*, Eli Maor — history of e from logarithms through calculus.
- [ ] *A History of Pi*, Petr Beckmann — standard popular history of π.
- [ ] *Trigonometric Delights*, Eli Maor — origins and development of trigonometry.
- [ ] *The Pythagorean Theorem: A 4000-Year History*, Eli Maor — deep dive on one theorem.
- [ ] *Euler: The Master of Us All*, William Dunham — Euler's mathematical legacy. Read after *Journey Through Genius* if Euler fascinates you.
- [ ] *Elements of Mathematics: From Euclid to Gödel*, John Stillwell — philosophical and foundational perspective on what mathematics is.

**Primary sources (for the genuinely curious):**

- [ ] Euclid's *Elements* (Heath translation)
  - The actual source for many foundational concepts (geometric mean, irrationality, basic number theory). Surprisingly readable in good translations. Read alongside or after Hartshorne.

**Rigorous Geometry and Trigonometry:**

These fill the gap left by school-level treatments — covering geometry and trigonometry with full proofs, historical context, and connections to modern algebra.

- [ ] Geometry: Euclid and Beyond, Robin Hartshorne
  - Walks through Euclid's *Elements* carefully, identifies the gaps that mathematicians found over 2000 years, presents Hilbert's modern axiomatization, then continues into non-Euclidean geometry, constructibility, and the impossibility theorems (squaring the circle, trisecting the angle).
  - The primary recommendation for rigorous Euclidean geometry. Matches your "how were the proofs constructed" interest exactly.
- [ ] Trigonometry, Gelfand & Saul
  - Small, beautiful book by the great Russian mathematician Gelfand. Treats trigonometry carefully and proof-fully. Respects the subject in a way most textbooks don't.
- [ ] *Calculus*, Michael Spivak — Chapter 15 (optional, for rigorous analytic trigonometry)
  - Defines sine and cosine analytically and proves their properties rigorously. Read this chapter if you want the full analytic foundation of trigonometry; you'll encounter it naturally during rigorous calculus study anyway.
- [ ] Euclidean and Non-Euclidean Geometries: Development and History, Marvin Greenberg (optional)
  - Historical development from Euclid through hyperbolic and elliptic geometries. Excellent on the parallel postulate's history.
- [ ] Irrational Numbers, Ivan Niven (optional)
  - Proofs that π and e are irrational (Niven's own short proof for π is famous). Covers transcendence too. The companion to questions like "how do we know π is irrational?"
- [ ] Introduction to Geometry, H.S.M. Coxeter (optional)
  - Euclidean, projective, and other geometries. Coxeter is a beloved expositor; genuinely enjoyable reading.

### Proofs

- [ ] How to Prove It, Velleman

### Analysis

- [ ] Understanding Analysis, Abbott
- [ ] Introductory Real Analysis, Kolmogorov & Fomin

### Linear Algebra

- [ ] Matrix Analysis, Horn & Johnson
  - Reference-grade. Matrix-specific results (norms, perturbation theory, positive definiteness, Perron-Frobenius). Genuinely useful for ML theory (concentration of matrix norms, eigenvalue perturbation) and numerical analysis. Different from Axler/Aluffi (which are about linear maps and modules) and from Trefethen & Bau (which is about algorithms).

### Probability

- [ ] Introduction to Probability, Blitzstein & Hwang
- [ ] A First Look at Rigorous Probability Theory, Rosenthal

### Algebraic Topology

- [ ] Algebraic Topology, Hatcher
  - Only if heading into topology/geometry research.
  - **Promoted to required if pursuing the physics track** (needed for QFT and string theory).
  - Style note: geometric and intuitive in spirit, but not always as rigorously careful as your Stage 1 books. Pair with Bredon for the rigor gaps.
- [ ] Topology and Geometry, Bredon (companion to Hatcher)
  - Rigor companion. Careful proofs, well-organized, covers both algebraic and differential topology. Ordering parallels Hatcher, making chapter-by-chapter pairing feasible.
  - Use when Hatcher's arguments feel hand-wavy or incomplete.

### Riemann Surfaces (for physics track)

- [ ] Algebraic Curves and Riemann Surfaces, Rick Miranda
  - Only needed if pursuing string theory. Companion to Stage P6 of physics list.

---

## Companion List

See `physics_reading_list.md` for the parallel physics curriculum (QM, GR, QFT, string theory) and how its tracks depend on this math list.

---

## Notes on Realistic Scope

This plan represents roughly 5–8 years of serious study at ~10 hrs/week. That is what a PhD-level foundation actually costs. If you want a faster track focused on a single application area (ML theory, control, or DSP) with narrower foundations, the core path would be: Stage 1 → Stage 2 Tracks A/B/E/F → targeted Stage 3/4 tracks for the chosen domain. That compresses to roughly 2–3 years.
