# CSIR NET Mathematics — Moodle XML Question Bank

A comprehensive MCQ question bank for **CSIR NET Mathematical Sciences** covering all 4 units of the official syllabus, formatted for direct import into **Moodle LMS**.

---

## About

This repository contains **600 multiple choice questions** (150 per unit) organized unit-wise as per the CSIR-UGC NET Mathematical Sciences syllabus. All questions include detailed explanations in the **General Feedback** field, making them suitable for both assessment and self-study.

---

## Repository Structure

```
TUTORDA-CSIR-MATH/
├── CSIR_MATH_Unit1_Analysis.xml                        (150 questions)
├── CSIR_MATH_Unit2_Algebra_ComplexAnalysis_Topology.xml (150 questions)
├── CSIR_MATH_Unit3_DiffEq_Mechanics.xml                (150 questions)
├── CSIR_MATH_Unit4_Probability_Statistics.xml          (150 questions)
└── README.md
```

---

## Syllabus Coverage

### Unit 1 — Analysis (150 questions)
| Subtopic | Questions |
|----------|-----------|
| Real Analysis (Sequences, Series, Continuity, Differentiability, Riemann Integration) | 40 |
| Metric Spaces (Completeness, Compactness, Baire Category, Connectedness) | 25 |
| Lebesgue Integration & Measure Theory | 20 |
| Linear Algebra (Rank-Nullity, Eigenvalues, Diagonalizability, Jordan Form) | 25 |
| Multivariable Calculus (Inverse/Implicit Function Theorems, Stokes' Theorem) | 20 |
| Complex Analysis Basics (Cauchy-Riemann, Analytic Functions) | 20 |

### Unit 2 — Algebra, Complex Analysis & Topology (150 questions)
| Subtopic | Questions |
|----------|-----------|
| Complex Analysis (Cauchy's Theorem, Residues, Conformal Maps, Liouville, Jensen's Formula) | 40 |
| Group Theory (Lagrange, Sylow Theorems, Normal Subgroups, Automorphisms, S_n) | 35 |
| Ring & Field Theory (Integral Domains, Maximal Ideals, UFD, Eisenstein, Finite Fields) | 35 |
| Topology (Hausdorff, Connectedness, Compactness, Tychonoff, Separation Axioms) | 40 |

### Unit 3 — Differential Equations & Mechanics (150 questions)
| Subtopic | Questions |
|----------|-----------|
| Ordinary Differential Equations (Picard's Theorem, Wronskian, Sturm-Liouville, Stability) | 30 |
| Partial Differential Equations (Classification, Heat/Wave/Laplace, Characteristics, Shocks) | 30 |
| Numerical Analysis (Newton-Raphson, RK4, Gaussian Elimination, Interpolation, Splines) | 25 |
| Calculus of Variations (Euler-Lagrange, Brachistochrone, Isoperimetric, Hamilton's Principle) | 25 |
| Classical Mechanics (Lagrangian, Hamiltonian, Noether's Theorem, Rigid Body, Scattering) | 25 |
| Linear Integral Equations (Fredholm, Volterra, Neumann Series, Hilbert-Schmidt) | 15 |

### Unit 4 — Probability & Statistics (150 questions)
| Subtopic | Questions |
|----------|-----------|
| Probability Theory (Borel-Cantelli, Characteristic Functions, Convergence Modes, CLT, LLN, LIL) | 35 |
| Probability Distributions (Normal, Poisson, Exponential, Chi-squared, Extreme Value, Stable) | 30 |
| Statistical Inference (MLE, Cramér-Rao, Sufficiency, UMVUE, Bayesian Estimation, Confidence Intervals) | 35 |
| Testing of Hypotheses (Neyman-Pearson, UMP, Chi-square, ANOVA, Nonparametric, LRT) | 20 |
| Stochastic Processes (Markov Chains, Brownian Motion, Martingales, Renewal Theory, CTMC, Itô Calculus) | 20 |
| Sampling Theory (SRSWOR, Stratified, Cluster, Ratio/Regression Estimators, Bootstrap) | 10 |

---

## Question Format

- **Type:** Multiple Choice (4 options, single correct answer)
- **Correct Answer Fraction:** `100`
- **Wrong Answer Fraction:** `0`
- **Answer Explanation:** Full solution provided in `<generalfeedback>` field
- **Math Rendering:** LaTeX notation (`\(...\)` inline, `\[...\]` display) — rendered via Moodle's MathJax filter
- **Answer Shuffling:** Enabled by default
- **Penalty:** 0.25 (negative marking compatible)
- **Categories:** Auto-organized in Moodle's Question Bank by Unit → Subtopic

---

## How to Import into Moodle

1. Log in to your **Moodle** site as Administrator or Teacher
2. Go to your course → **Question Bank** → **Import**
3. Select format: **Moodle XML**
4. Upload the desired XML file(s)
5. Click **Import** — questions will appear in the Question Bank under the respective categories

> Import one file at a time or all four to build the complete question bank of 600 questions.

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
- **MathJax filter** enabled (Admin → Plugins → Filters → MathJax) for proper LaTeX rendering

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
