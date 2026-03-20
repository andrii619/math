# Reading List

Prioritize books that emphasize deep intuitive understanding of topics, have plenty of discussions and examples, and also emphasise rigorous proofs.
Some examples of the style of books we are aiming for: "Real Analysis" by Jay Cummings, "Linear Algebra Done Right" by Axler, "Understanding Analysis" by Abbott. 

Goals:

* Achieve mathematical maturity 
* Get to a level of deep and intuitive understanding of why things work in areas of machine learning, control theory, digital signal processing.
* avoid 'recipe' books that show methods but do not show proofs or why things work. For example, a lot of statistics and ML books are like this. 
* Be able to create and prove own theories.

## Stage 1

Books within the same track (A, B, C) are sequential. Different tracks can be read in parallel.

### Track A: Analysis

- [X] Proofs, Jay Cummings
- [O] Real Analysis, Jay Cummings

### Track B: Linear Algebra

- [ ] Introduction to Linear Algebra, Strang
  - Emphasize: Ch 1-7 (core linear algebra). Ch 8-12 (applications, numerical methods) are useful but less critical since Trefethen & Bau covers numerical LA later.
- [ ] Linear Algebra Done Right, Axler
  - Read cover to cover. Every chapter builds on the last.
- [ ] Linear and Geometric Algebra, Macdonald
  - Emphasize: Part II (geometric algebra). Part I overlaps with Strang/Axler — skim for review.

### Track C: Foundations (short reads, parallel with A or B)

- [ ] Naive Set Theory, Halmos
  - Emphasize: Ch 1-18 (sets, relations, functions, cardinality). Ch 19-25 (ordinals, cardinal arithmetic, axiom of choice) — read for exposure but don't get stuck.
- [ ] Visual Group Theory
- [ ] How to Solve It, Polya
  - Short read. Builds proof instincts and mathematical thinking habits — how mathematicians approach problems they haven't seen before.
- [ ] Journey Through Genius: Great Theorems of Mathematics, by William Dunham

### After Tracks A + B:

- [ ] Vector Calculus, Linear Algebra, and Differential Forms: A Unified Approach by Hubbard & Hubbard
  - Emphasize: Ch 1-4 (derivatives in R^n, inverse/implicit function theorems, integration). Ch 5-6 (differential forms, manifolds) can be deferred — Needham covers this more intuitively later.

---

## Stage 2

Books within the same track are sequential. Different tracks can be read in parallel.

### Track A: Analysis

- [ ] Analysis I and II, Terrence Tao
  - Analysis I: Skim chapters on construction of reals (unique to Tao), focus on the later chapters building on Cummings.
  - Analysis II: Read carefully — metric spaces, Lebesgue integration, multivariable differential calculus are new and critical.
- [ ] Measures, Integrals, and Martingales by Rene Schilling
  - Read cover to cover. This is the measure theory foundation for Durrett and Vershynin.
  - Companion: "Counterexamples in Measure and Integration" by Schilling. Use as a reference alongside each chapter — don't read sequentially.
- [ ] Fourier Analysis: An Introduction by Stein and Shakarchi
  - Emphasize: Ch 1-6 (Fourier series, Fourier transform, applications). Ch 7-8 (finite Fourier analysis, Dirichlet's theorem) are less critical for DSP/ML.
- [ ] Visual Complex Analysis, Tristan Needham
  - Can be read selectively. Emphasize: Ch 1-8 (geometry of complex maps, Mobius transformations, conformal mappings, contour integration). Ch 9-12 are more specialized.

### Track B: Differential Equations and Dynamical Systems

- [ ] Ordinary Differential Equations, by V.I. Arnold
  - Emphasize: Ch 1-4 (phase spaces, vector fields, linear systems, stability). Ch 5-6 (oscillations, symmetry) are enriching but less essential.
- [ ] Nonlinear Dynamics and Chaos, by Steven Strogatz
  - Emphasize: Ch 1-9 (bifurcations, phase plane, limit cycles, Lorenz system). Ch 10-12 (fractals, strange attractors) are fascinating but less directly applicable.

### Track C: Probability (after Track A: Schilling)

- [ ] Probability, Durrett

### Track D: Independent (parallel with any track)

- [ ] Numerical Linear Algebra, by Trefethen & Bau
- [ ] Convex Optimization, by Boyd
  - Emphasize: Ch 1-5 (convex sets, functions, optimization problems, duality). Ch 6-11 (algorithms, applications) are useful but more computational/applied.
- [ ] Statistical Inference, by Casella & Berger
- [ ] Abstract Algebra, Pinter
- [ ] Topology, by Munkres
  - Emphasize: Part I only (Ch 1-8: topological spaces, connectedness, compactness, metric spaces, countability/separation axioms). Part II (algebraic topology) is a separate subject — skip unless heading toward Hatcher.

## Stage 3

Different tracks can be read in parallel.

### Track A: Probability (after Stage 2 Track C)

- [ ] High-Dimensional Probability: An Introduction with Applications in Data Science by Roman Vershynin
- [ ] Stochastic Differential Equations, by Oksendal (also needs Track B: Kreyszig)

### Track B: Functional Analysis

- [ ] Introductory Functional Analysis with Applications, by Kreyszig

### Track C: Geometry (parallel with any track)

- [ ] Visual Differential Geometry, Needham

---

## Stage 4

Pure math first — this stage is for applying that foundation to the target domains. Different tracks can be read in parallel.

### Track A: Control (after Stage 2 Track B + Stage 3 Track B)

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

### Track C: Machine Learning Theory (after Stage 3 Track A)

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

### Functional Analysis

- [ ] Introductory Real Analysis, by Kolmogorov & Fomin

### Probability

- [ ] Introduction to Probability, by Blitzstein & Hwang
- [ ] First Look At Rigorous Probability Theory, Rosenthal

### Linear Algebra

- [ ] Introduction to Linear and Matrix Algebra, by Nathaniel Johnston
- [ ] Advanced Linear and Matrix Algebra, by Nathaniel Johnston


### Digital Signal Processing

- [ ] Kalman Filter from the Ground Up, by Alex Becker

### Control

- [ ] Feedback Control of Dynamic Systems, by Franklin and Powell



## Other

- [ ] Algebraic Topology, by Hatcher

