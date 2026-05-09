# CSIR NET Mathematics — Moodle XML Question Bank

A comprehensive MCQ question bank for **CSIR NET Mathematical Sciences** covering all 4 units of the official syllabus, formatted for direct import into **Moodle LMS**.

---

## About

This repository contains **~123 multiple choice questions** organized unit-wise as per the CSIR-UGC NET Mathematical Sciences syllabus. All questions include detailed explanations in the **General Feedback** field, making them suitable for both assessment and self-study.

---

## Repository Structure

```
TUTORDA-CSIR-MATH/
├── CSIR_MATH_Unit1_Analysis.xml
├── CSIR_MATH_Unit2_Algebra_ComplexAnalysis_Topology.xml
├── CSIR_MATH_Unit3_DiffEq_Mechanics.xml
├── CSIR_MATH_Unit4_Probability_Statistics.xml
└── README.md
```

---

## Syllabus Coverage

### Unit 1 — Analysis
| Subtopic | Questions |
|----------|-----------|
| Set Theory (Countability, Cantor Set) | 5 |
| Real Number System (Archimedean Property, Supremum, Infimum) | 5 |
| Sequences and Series (Bolzano-Weierstrass, Heine-Borel, Convergence) | 5 |
| Continuity and Differentiability (MVT, Uniform Continuity, Weierstrass) | 5 |
| Riemann Integration (Lebesgue Criterion, FTC, Darboux Sums) | 5 |
| Linear Algebra (Rank-Nullity, Eigenvalues, Diagonalizability) | 6 |
| Metric Spaces (Open Sets, Completeness, Baire Category, Compactness) | 5 |

### Unit 2 — Algebra, Complex Analysis & Topology
| Subtopic | Questions |
|----------|-----------|
| Complex Analysis (C-R Equations, Cauchy's Theorem, Liouville, Residues, Möbius) | 7 |
| Group Theory (Lagrange, Normal Subgroups, Sylow, Cayley) | 5 |
| Ring Theory (Integral Domains, Maximal Ideals, UFD, Eisenstein) | 4 |
| Field Theory & Number Theory (Finite Fields, CRT, Euler's φ, Fermat, Pigeon-hole) | 5 |
| Topology (Heine-Borel, Connectedness, Hausdorff, Tychonoff, Separation Axioms) | 5 |

### Unit 3 — Differential Equations & Mechanics
| Subtopic | Questions |
|----------|-----------|
| Ordinary Differential Equations (Picard's Theorem, Wronskian, Variation of Parameters, Sturm-Liouville) | 6 |
| Partial Differential Equations (Classification, Laplace, Heat, Wave, Lagrange's Method) | 5 |
| Numerical Analysis (Newton-Raphson, Simpson's Rule, Gauss Elimination, RK4, Interpolation) | 5 |
| Calculus of Variations (Euler-Lagrange, Brachistochrone, Isoperimetric Problem) | 3 |
| Classical Mechanics (Lagrangian, Hamilton's Equations, Conservation, Poisson Brackets) | 4 |
| Linear Integral Equations (Fredholm, Volterra, Neumann Series, Symmetric Kernels) | 3 |

### Unit 4 — Probability & Statistics
| Subtopic | Questions |
|----------|-----------|
| Probability Theory (Bayes' Theorem, Independence, Chebyshev, CLT, LLN) | 5 |
| Probability Distributions (Poisson, Normal, Exponential, Binomial, Chi-squared) | 5 |
| Statistical Inference (MLE, Unbiased Estimators, Cramér-Rao Bound, Confidence Intervals) | 4 |
| Testing of Hypotheses (Type I/II Errors, Neyman-Pearson Lemma, Chi-square Test, p-value) | 4 |
| Markov Chains & Stochastic Processes (Markov Property, Stationary Distribution, Recurrence, Poisson Process) | 4 |
| Sampling Theory (SRS, Stratified Sampling, Systematic Sampling, Spearman's Rank Correlation) | 4 |

---

## Question Format

- **Type:** Multiple Choice (4 options, single correct answer)
- **Correct Answer Fraction:** `100`
- **Wrong Answer Fraction:** `0`
- **Answer Explanation:** Full solution provided in `<generalfeedback>` field
- **Math Rendering:** LaTeX notation (`\(...\)`) — rendered via Moodle's MathJax filter
- **Answer Shuffling:** Enabled by default
- **Categories:** Auto-organized in Moodle's Question Bank by Unit → Subtopic

---

## How to Import into Moodle

1. Log in to your **Moodle** site as Administrator or Teacher
2. Go to your course → **Question Bank** → **Import**
3. Select format: **Moodle XML**
4. Upload the desired XML file(s)
5. Click **Import** — questions will appear in the Question Bank under the respective categories

> Import one file at a time or all four to build the complete question bank.

---

## Exam Pattern Reference

| Part | Questions | To Attempt | Coverage |
|------|-----------|------------|----------|
| Part A | 20 | 15 | General Aptitude |
| Part B | 40 | 25 | Core Mathematics (Units 1–4) |
| Part C | 60 | 20 | Advanced / Analytical (Units 1–4) |

---

## Prerequisites for Moodle

- Moodle version 3.x or higher
- **MathJax filter** enabled (Admin → Plugins → Filters → MathJax) for proper rendering of mathematical symbols

---

## Contributing

Contributions are welcome! To add more questions:

1. Fork this repository
2. Add questions following the existing Moodle XML format
3. Submit a Pull Request with a description of topics added

---

## License

This question bank is developed by **TUTORDA LMS** for educational purposes.  
Free to use for teaching, self-study, and academic institutions.

---

## Contact

- **Organization:** TUTORDA LMS
- **Email:** jananissmiet@gmail.com
- **GitHub:** [tutorda007-beep](https://github.com/tutorda007-beep)
