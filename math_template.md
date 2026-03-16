
## Exercise Template

**Exercise (Cummings, Sec. 2.3 #7).**  
*Claim:* If $\sum_{n=1}^\infty a_n$ converges absolutely, then it converges.

**Proof.**  
Assume $\sum_{n=1}^\infty |a_n|$ converges. Let $s_n=\sum_{k=1}^n a_k$.
Fix $\varepsilon>0$. Since $\sum |a_n|$ converges, there exists $N$ such that
for all $m>n\ge N$,
$$
\sum_{k=n+1}^m |a_k|<\varepsilon.
$$
Then for $m>n\ge N$,
$$
|s_m-s_n|=\left|\sum_{k=n+1}^m a_k\right|
\le \sum_{k=n+1}^m |a_k|<\varepsilon.
$$
So $(s_n)$ is Cauchy, hence convergent. $\square$

## Markdown (LaTeX) Math Cheat Sheet

*(Copy/paste this into your notes. Everything between `$...$` is inline math, and `$$...$$` is display math.)*

---

## 0) Inline vs display math

Inline: `$a^2+b^2=c^2$` → $a^2+b^2=c^2$
Inline math is for inserting a snippet of math into text lines.

Display:
Display math means display a block of math
$$
a^2+b^2=c^2
$$

$$
a^2+b^2=c^2
$$

---

## 1) Subscripts, superscripts, accents

* Sub/superscripts: $x_i,\ x_{i+1},\ x^2,\ x^{n+1}$
* Parentheses matter: $x_i^2,\ (x_i)^2$
* Overline / conjugate: $\overline{z}$
* Hat, tilde, dot: $\hat f,\ \tilde f,\ \dot x,\ \ddot x$
* Bar/vec: $\vec v$ (often $\mathbf v$ is preferred for vectors)
* Underline: $\underline{x}$

---

## 2) Fractions, roots, absolute values, norms

* Fraction: $\frac{a}{b}$
* Nested: $\frac{1}{1+\frac{1}{n}}$
* Square root: $\sqrt{2}$, $\sqrt[n]{x}$
* Absolute value: $\lvert x\rvert$
* Norm: $\lVert x\rVert$, $\lVert x\rVert_2$
* Floor/ceiling: $\lfloor x\rfloor,\ \lceil x\rceil$

---

## 3) Greek letters (common)

$\alpha \beta \gamma \delta \epsilon \varepsilon \eta \theta \lambda \mu \nu \pi \rho \sigma \tau \phi \varphi \psi \omega$

Uppercase: $\Gamma \Delta \Theta \Lambda \Pi \Sigma \Phi \Psi \Omega$

---

## 4) Logic & quantifiers

* For all / exists: $\forall x,\ \exists y$
* Such that: $\exists x\in A:\ P(x)$ or $\exists x\in A\ \text{s.t.}\ P(x)$
* And/or/not: $\land,\ \lor,\ \neg$
* Implies/iff: $\Rightarrow,\ \Leftarrow,\ \Leftrightarrow$
* Therefore: $\therefore$ (use sparingly)

---

## 5) Sets & set operations (set theory basics)

* Membership: $x\in A,\ x\notin A$
* Subset: $A\subseteq B$, proper subset: $A\subsetneq B$
* Union/intersection: $A\cup B,\ A\cap B$
* Difference: $A\setminus B$
* Complement: $A^c$ (sometimes $\complement A$)
* Empty set: $\varnothing$
* Power set: $\mathcal P(A)$
* Cartesian product: $A\times B$
* Set-builder: $\{x\in \mathbb R : x>0\}$ or $\{x\in\mathbb R \mid x>0\}$
* Disjoint union (sometimes): $A\bigsqcup B$

---

## 6) Common number systems and “blackboard bold”

* Naturals/integers/rationals/reals/complex: $\mathbb N,\ \mathbb Z,\ \mathbb Q,\ \mathbb R,\ \mathbb C$
* Finite field: $\mathbb F_p$ or $\mathbf F_p$
* Integers mod n: $\mathbb Z/n\mathbb Z$

---

## 7) Functions, maps, and relations

* Function notation: $f:A\to B$
* Value: $f(x)$
* Composition: $f\circ g$
* Image / preimage: $f(A),\ f^{-1}(B)$
* Restriction: $f\!\mid_A$
* Injective/surjective/bijective: $\text{injective},\ \text{surjective},\ \text{bijective}$
  (Often write: $f$ is injective.)
* Identity: $\operatorname{id}_A$
* Equivalence relation: $\sim$, quotient: $A/{\sim}$

---

## 8) Standard operators (use `\operatorname{}`)

These typeset like proper math operators:

* $\operatorname{im}(T)$, $\ker(T)$, $\operatorname{rank}(A)$
* $\Re(z),\ \Im(z)$ (also $\operatorname{Re}$, $\operatorname{Im}$)
* `$\operatorname{span}(S)$`, `$\operatorname{diag}(\cdots)$`
* `$\operatorname{tr}(A)$`, `$\det(A)$`
* `$\operatorname{Hom}(G,H)$`, `$\operatorname{End}(V)$`
* `$\operatorname{Aut}(G)$`, `$\operatorname{Gal}(L/K)$`

---

## 9) Summations, products, and sequences/series

* Sum: $\sum_{k=1}^n a_k$
* Infinite series: $\sum_{n=1}^\infty a_n$
* Product: $\prod_{k=1}^n a_k$
* Sequence: $(a_n)_{n\ge 1}$
* Big-O/little-o: $O(n),\ o(n)$

---

## 10) Calculus & analysis

### Limits and continuity

* Limit: $\lim_{n\to\infty} a_n$
* One-sided: $\lim_{x\to 0^+} f(x)$
* Continuity: $f$ is continuous at $a$
* Convergence in a metric: $x_n\to x$

## Equivalence

* $\cong$
* $\equiv$
* $\ncong$
* $\simeq$

### Derivatives

* Derivative: $f'(x)$, $\frac{d}{dx}f(x)$
* Partial: `$\frac{\partial f}{\partial x}$`, `$\nabla f$`
* Gradient/div/curl: `$\nabla f,\ \nabla\cdot F,\ \nabla\times F$`
* Jacobian: `$\mathrm Df$` or `$\frac{\partial(f_1,\dots,f_m)}{\partial(x_1,\dots,x_n)}$`

### Integrals

* Definite: `$\int_a^b f(x)\,dx$`
* Indefinite: `$\int f(x)\,dx$`
* Double: `$\int\!\!\int_D f\,dA$`
* With measure: `$\int f\,d\mu$`
* Expectation (probability): `$\mathbb E[X]$` (see below)

### Standard spaces/notation

* Open ball: `$B_r(x)$`
* Closure/interior/boundary: `$\overline{A},\ A^\circ,\ \partial A$`
* Sup/inf: `$\sup A,\ \inf A$`
* Limsup/liminf: `$\limsup a_n,\ \liminf a_n$`
* Indicator: `$\mathbf 1_A$` or `$\mathbb 1_A$`

---

## 11) Complex analysis essentials

* Complex number: `$z=x+iy$`, `$\overline z=x-iy$`
* Modulus/argument: `$|z|,\ \arg z$`
* Real/imag parts: `$\Re z,\ \Im z$`
* Exponential: `$e^{i\theta}=\cos\theta+i\sin\theta$`
* Cauchy–Riemann: `$u_x=v_y,\ u_y=-v_x$`
* Contour integral: `$\int_\gamma f(z)\,dz$`
* Residue: `$\operatorname{Res}(f,a)$`

---

## 12) Linear algebra essentials

### Vectors and matrices

* Bold vectors (common): `$\mathbf v,\ \mathbf x$`
* Matrix: `$A\in\mathbb R^{m\times n}$`
* Transpose: `$A^\top$`
* Conjugate transpose: `$A^*$` or `$A^\dagger$`
* Inverse: `$A^{-1}$`

### Inner products and projections

* Inner product: `$\langle x,y\rangle$`
* Orthogonal: `$x\perp y$`
* Orthogonal complement: `$W^\perp$`
* Span: `$\operatorname{span}\{v_1,\dots,v_k\}$`

### Eigenvalues, SVD, etc.

* Eigen: `$Av=\lambda v$`
* Spectrum: `$\sigma(A)$`
* Trace/det: `$\operatorname{tr}(A),\ \det(A)$`
* SVD: `$A=U\Sigma V^\top$`
* Norms: `$\|A\|,\ \|x\|_2,\ \|x\|_1,\ \|x\|_\infty$`

---

## 13) Abstract algebra essentials

### Groups

* Group operation: `$G$ with $\cdot$` (often just juxtaposition)
* Identity/inverse: `$e,\ g^{-1}$`
* Subgroup: `$H\le G$`, normal: `$N\trianglelefteq G$`
* Cosets: `$gH,\ Hg$`
* Quotient: `$G/N$`
* Homomorphism: `$\varphi:G\to H$`
* Kernel/image: `$\ker\varphi,\ \operatorname{im}\varphi$`
* Isomorphism: `$G\cong H$`
* Direct product: `$G\times H$`
* Generated subgroup: `$\langle S\rangle$`

### Rings/fields

* Ideal: `$I\trianglelefteq R$` (some write `$I\lhd R$`)
* Quotient ring: `$R/I$`
* Units: `$R^\times$`
* Polynomial ring: `$R[x]$`
* Field extension: `$L/K$`

---

## 14) Probability notation (since it shows up in analysis/ML)

* Probability: `$\mathbb P(A)$`
* Conditional: `$\mathbb P(A\mid B)$`
* Expectation: `$\mathbb E[X]$`, conditional: `$\mathbb E[X\mid \mathcal F]$`
* Variance: `$\operatorname{Var}(X)$`
* Distribution: `$X\sim \mathcal N(0,1)$`, or `$X\sim \mu$`
* Independence: `$X\perp\!\!\!\perp Y$` (common), or `$X$ independent of $Y$`
* Almost surely: `$\text{a.s.}$`, in probability: `$\xrightarrow{p}$`, in distribution: `$\xrightarrow{d}$`
* Indicator: `$\mathbf 1_A$`

---

## 15) Arrows, equivalences, and common symbols

* Maps: `$\to,\ \mapsto$`
* Convergence: `$\to,\ \Rightarrow$` (be careful: use $\Rightarrow$ for implication, not limits)
* Approx: `$\approx$`, asymptotic: `$\sim$`
* Proportional: `$\propto$`
* Dots: `$\cdots,\ \ldots,\ \vdots,\ \ddots$`
* Ellipsis in sets: `$\{1,2,\dots,n\}$`

---

## 16) Alignment for multi-line derivations (display math)

```tex
$$
\begin{aligned}
\sum_{k=1}^n k
&= \frac{n(n+1)}{2},\\
\int_0^1 x^p\,dx
&= \frac{1}{p+1}.
\end{aligned}
$$
```

$$
\begin{aligned}
\sum_{k=1}^n k
&= \frac{n(n+1)}{2},\
\int_0^1 x^p,dx
&= \frac{1}{p+1}.
\end{aligned}
$$

---

## 17) Theorem/proof formatting (clean and consistent)

```markdown
**Theorem.** *(statement)*

**Proof.**  
(text...)  
$\square$
```

---

## 18) Quick “symbol lookup” line (copyable)

`$\in \notin \subseteq \subsetneq \cup \cap \setminus \varnothing \times \to \mapsto \forall \exists \Rightarrow \Leftrightarrow \sum \prod \lim \sup \inf \langle \rangle \lVert \rVert \Re \Im \ker \operatorname{im} \det \operatorname{tr}$`

```
```