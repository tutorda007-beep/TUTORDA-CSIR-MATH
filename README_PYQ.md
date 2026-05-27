# CSIR NET Mathematics — Previous Year Pattern Question Bank (Moodle XML)

A **Part B and Part C** question bank for **CSIR-UGC NET Mathematical Sciences**, modelled on previous year exam patterns. All 4 units are covered with separate XML files, ready for direct import into **Moodle LMS**.

---

## Repository Structure

```
CSIR MATH VERSION 1/
├── CSIR_NET_PYQ_Unit1_Analysis.xml                          (57 questions)
├── CSIR_NET_PYQ_Unit2_Algebra_ComplexAnalysis_Topology.xml  (50 questions)
├── CSIR_NET_PYQ_Unit3_DiffEq_Mechanics.xml                  (47 questions)
├── CSIR_NET_PYQ_Unit4_Probability_Statistics.xml            (49 questions)
└── README_PYQ.md
```

**Total: 203 questions** (121 Part B + 82 Part C)

---

## Exam Pattern Reference

| Part | Questions | To Attempt | Marks Each | Negative Marking |
|------|-----------|------------|------------|------------------|
| Part A | 20 | 15 | 2 | −0.5 |
| Part B | 40 | 25 | **3** | **−1** |
| Part C | 60 | 20 | **4.75** | **−1.25** |

> Part B: Single correct MCQ | Part C: Analytical / higher-order MCQ

---

## Question Format

| Property | Part B | Part C |
|----------|--------|--------|
| Type | Multiple Choice (4 options) | Multiple Choice (4 options) |
| Correct fraction | `100` | `100` |
| Wrong fraction | `0` | `0` |
| `defaultgrade` | `3.0` | `4.75` |
| `penalty` | `0.3333` | `0.2632` |
| Feedback | Full solution with LaTeX | Full solution with LaTeX |
| Answer shuffling | Enabled | Enabled |

---

## Syllabus Coverage

### Unit 1 — Analysis (57 questions)

| Category | Part B | Part C |
|----------|--------|--------|
| Real Analysis (Sequences, Series, Continuity, Differentiability, Integration) | 20 | 15 |
| Linear Algebra (Rank-Nullity, Eigenvalues, Diagonalization, Jordan Form, SVD) | 15 | 7 |

**Topics include:** Cauchy sequences, Bolzano-Weierstrass, p-series, alternating series, Weierstrass M-test, Riemann integrability (Lebesgue criterion), Cantor set, Baire Category theorem, Arzela-Ascoli, Stone-Weierstrass, Dominated Convergence, Banach fixed point, Beta/Gamma functions, Cayley-Hamilton, Spectral theorem, Positive definiteness, Jordan normal form, Singular value decomposition.

---

### Unit 2 — Algebra, Complex Analysis & Topology (50 questions)

| Category | Part B | Part C |
|----------|--------|--------|
| Complex Analysis (CR equations, Cauchy's theorem, Residues, Singularities, Conformal maps) | 10 | 5 |
| Group Theory (Lagrange, Sylow, Normal subgroups, Isomorphism theorems, S_n) | 6 | 2 |
| Ring & Field Theory (Maximal ideals, Eisenstein, Integral domains, Finite fields, Galois) | 4 | 1 |
| Topology (Hausdorff, Compactness, Tychonoff, Connectedness, Fundamental group) | 5 | 4 |

**Topics include:** Cauchy-Riemann equations, Cauchy integral formula, Liouville's theorem, Residue theorem, Rouché's theorem, Open mapping theorem, Möbius transformations, Lagrange's theorem, Sylow theorems, First isomorphism theorem, Eisenstein's criterion, Finite fields GF(p^n), Hausdorff spaces, Tychonoff theorem, Urysohn metrization, Fundamental group π₁(S¹) ≅ ℤ, GL_n(ℝ) connectedness.

---

### Unit 3 — Differential Equations & Mechanics (47 questions)

| Category | Part B | Part C |
|----------|--------|--------|
| ODE (Picard's theorem, Wronskian, Sturm comparison, Stability, Bessel's equation) | 7 | 2 |
| PDE (Classification, Wave/Heat/Laplace equations, Characteristics, d'Alembert) | 5 | 2 |
| Numerical Analysis (Newton-Raphson, Trapezoidal rule, RK4, Gaussian elimination) | 4 | 2 |
| Calculus of Variations & Mechanics (Euler-Lagrange, Lagrangian, Hamiltonian, Noether) | 4 | 2 |
| Advanced (Green's function, Sturm-Liouville, Heat kernel, Fredholm equations) | — | 4 |

**Topics include:** Picard-Lindelöf theorem, Abel's identity for Wronskian, Sturm comparison, Regular singular points (Frobenius method), PDE classification (Δ = B²−4AC), Maximum principle, d'Alembert solution, Euler-Lagrange equation, Hamilton's canonical equations, Noether's theorem, Brachistochrone (cycloid), Isoperimetric inequality, Newton-Raphson (quadratic convergence), RK4 (O(h⁴) error), Banach fixed-point iteration, LU decomposition.

---

### Unit 4 — Probability & Statistics (49 questions)

| Category | Part B | Part C |
|----------|--------|--------|
| Probability Theory (Borel-Cantelli, CLT, SLLN, Characteristic functions, Convergence modes) | 9 | 3 |
| Distributions (Poisson, Normal, Exponential, Chi-squared) | 4 | — |
| Statistical Inference (MLE, Cramér-Rao, Sufficiency, UMVUE, Confidence intervals) | 5 | 4 |
| Stochastic Processes (Markov chains, Brownian motion, Martingales) | 2 | 3 |

**Topics include:** Borel-Cantelli lemmas, CLT (Lindeberg-Lévy), SLLN (Kolmogorov), characteristic functions (uniqueness), convergence hierarchy (a.s. ⟹ in probability ⟹ in distribution), MLE for Normal/Poisson, Cramér-Rao lower bound, Fisher-Neyman factorization, Rao-Blackwell / UMVUE, Neyman-Pearson lemma, Wilks' theorem (LRT ∼ χ²), tower property of conditional expectation, martingale definition, stationary distribution of Markov chains, Bayesian posterior.

---

## Moodle Import Instructions

1. Log in to Moodle as **Administrator** or **Teacher**
2. Navigate to your course → **Question Bank** → **Import**
3. Select format: **Moodle XML**
4. Upload the desired XML file
5. Click **Import**

Questions will appear under:
```
$course$ / CSIR NET Mathematics PYQ / Unit X / Part B - <Subtopic>
$course$ / CSIR NET Mathematics PYQ / Unit X / Part C - <Subtopic>
```

> Import one unit at a time. All 4 files can coexist in the same Question Bank.

---

## Prerequisites

- Moodle 3.x or higher
- **MathJax filter** enabled for LaTeX rendering:
  `Site Administration → Plugins → Filters → MathJax`

---

## Difference from the Original Question Bank

| Feature | Original Bank | This PYQ Bank |
|---------|--------------|---------------|
| Questions per unit | 150 | 47–57 |
| Focus | Topic-wise practice | Previous year pattern |
| Part labels | Not separated | Part B / Part C labelled |
| Marks per question | 1 (uniform) | 3 (Part B) / 4.75 (Part C) |
| Negative marking | 0.25 | 0.3333 (Part B) / 0.2632 (Part C) |
| Difficulty | Mixed | Part C harder / analytical |

---

## Contact

- **Organization:** TUTORDA LMS
- **Email:** jananissmiet@gmail.com
- **GitHub:** [tutorda007-beep](https://github.com/tutorda007-beep)
