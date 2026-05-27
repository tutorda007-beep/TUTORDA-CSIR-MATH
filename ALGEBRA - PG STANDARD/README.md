# Advanced Algebra (M.Sc. Mathematics) — Moodle Question Bank

## Overview

This folder contains **Moodle XML question banks** for the course **Advanced Algebra (M.Sc. Mathematics)**, designed to support learning and assessment aligned with the **CSIR NET Mathematics** syllabus — Algebra section.

The question banks are organised in two series:

| Series | Prefix | Purpose | Type |
|--------|--------|---------|------|
| Chapter-wise Practice | `Chapter N — Unit ...` | Conceptual practice with parametric/calculated questions | `calculatedmulti` |
| CSIR NET Previous Year Pattern | `CSIR PYQ — Unit ...` | MCQ in CSIR NET exam style with full solutions | `multichoice` |

---

## File Listing

### Series 1 — Chapter-wise Practice Questions

| File | Unit | Topics |
|------|------|--------|
| `Chapter 1 — Unit I — Sylow theorems, solvable and nilpotent groups.xml` | I | Sylow theorems, solvable groups, nilpotent groups |
| `Chapter 2 — Unit II — Rings, ideals, polynomial rings and unique factorisation d.xml` | II | Rings, ideals, polynomial rings, UFDs |
| `Chapter 3 — Unit III — Modules, submodules and modules over PIDs.xml` | III | Modules, submodules, structure theorem over PIDs |
| `Chapter 4 — Unit IV — Field extensions, algebraic and transcendental extensions.xml` | IV | Field extensions, algebraic vs. transcendental elements |
| `Chapter 5 — Unit V — Galois theory and solvability by radicals.xml` | V | Galois theory, solvability by radicals |

**Question type:** `calculatedmulti` (parametric variables — each attempt generates fresh values)  
**Purpose:** Regular practice, formative assessment, homework  
**Marks:** 1 mark per question, 1/3 penalty

---

### Series 2 — CSIR NET PYQ Pattern Questions

| File | Unit | Questions | Topics |
|------|------|-----------|--------|
| `CSIR PYQ — Unit I — Sylow theorems, solvable and nilpotent groups.xml` | I | 30 | Sylow's three theorems, solvable/nilpotent groups, Jordan–Hölder theorem, derived series, class equation, Frattini subgroup |
| `CSIR PYQ — Unit II — Rings, ideals, polynomial rings and UFD.xml` | II | 30 | Eisenstein's criterion, prime/maximal ideals, UFD/PID/Euclidean hierarchy, Gauss's Lemma, Noetherian rings, nilradical, Jacobson radical |
| `CSIR PYQ — Unit III — Modules, submodules and modules over PIDs.xml` | III | 25 | Structure theorem for fg modules over PIDs, free/projective/injective modules, torsion, Cayley–Hamilton, Smith Normal Form, Schur's Lemma, Nakayama's Lemma |
| `CSIR PYQ — Unit IV — Field extensions, algebraic and transcendental extensions.xml` | IV | 25 | Tower law, minimal polynomials, splitting fields, normal/separable extensions, cyclotomic fields, Frobenius map, algebraic closure, primitive element theorem |
| `CSIR PYQ — Unit V — Galois theory and solvability by radicals.xml` | V | 25 | Galois correspondence, specific Galois group computations, Abel–Ruffini theorem, Kronecker–Weber theorem, Kummer extensions, cyclotomic polynomials |

**Question type:** `multichoice` (fixed 4-option MCQ)  
**Purpose:** CSIR NET exam preparation, summative assessment, mock tests  
**Marks:** 2 marks per question, 0.25 penalty (mirrors CSIR NET Part B scheme)  
**Total questions:** 135 MCQs

**Key feature:** Every question includes a **detailed solution with mathematical reasoning** in the `<generalfeedback>` section — visible to students after submission.

---

## CSIR NET Syllabus Coverage

### Unit I — Groups
- Sylow's First Theorem (existence of Sylow subgroups)
- Sylow's Second Theorem (conjugacy of Sylow subgroups)
- Sylow's Third Theorem (congruence and divisibility conditions for n_p)
- Applications: proving groups of specific orders are cyclic, abelian, or non-simple
- Solvable groups and derived series
- Nilpotent groups and central series
- Jordan–Hölder theorem and composition factors
- p-groups: non-trivial center, maximal subgroups, Frattini subgroup

### Unit II — Rings
- Rings, subrings, ideals, quotient rings
- Prime and maximal ideals; characterisation via quotient rings
- Euclidean domains → PIDs → UFDs → Integral domains (strict hierarchy)
- Polynomial rings: irreducibility tests (Eisenstein, rational root, reduction mod p)
- Gauss's Lemma; Hilbert's Basis Theorem
- Nilradical and Jacobson radical
- Chinese Remainder Theorem; Krull dimension

### Unit III — Modules
- Modules, submodules, quotient modules, module homomorphisms
- Structure theorem for finitely generated modules over PIDs (invariant factor and primary decompositions)
- Free, projective, and injective modules
- Torsion submodule; torsion-free and divisible modules
- Applications: classification of finitely generated abelian groups, rational canonical form, Jordan normal form
- Cayley–Hamilton theorem; Schur's Lemma; Nakayama's Lemma

### Unit IV — Fields
- Field extensions: degree, tower law, algebraic and transcendental elements
- Minimal polynomial; simple extensions F(α) ≅ F[x]/(min poly)
- Finite fields F_{p^n}; Frobenius endomorphism
- Cyclotomic extensions; degree [Q(ζ_n):Q] = φ(n)
- Normal and separable extensions; splitting fields; algebraic closure
- Primitive Element Theorem; transcendence degree

### Unit V — Galois Theory
- Galois extensions (normal + separable); |Gal(K/F)| = [K:F]
- Fundamental Theorem of Galois Theory (Galois correspondence)
- Computation of Galois groups: Q(√2)/Q, Q(√2,√3)/Q, Q(ζ_n)/Q, splitting fields
- Solvable groups and solvability by radicals
- Abel–Ruffini Theorem (general quintic not solvable)
- Kronecker–Weber Theorem (abelian extensions of Q)
- Kummer extensions and cyclotomic polynomials Φ_n(x)

---

## Moodle Import Instructions

### How to Import into Moodle

1. Log in to Moodle as an instructor.
2. Navigate to your course → **Question Bank** → **Import**.
3. Select **Moodle XML format**.
4. Upload the desired `.xml` file.
5. Click **Import** to confirm.

### Recommended Import Order

Import Series 1 first (Chapter-wise), then Series 2 (CSIR PYQ), so both sets appear in the question bank under their respective categories.

### Category Structure in Moodle

After import, questions appear under:

```
Course Question Bank
└── Advanced Algebra (M.Sc. Mathematics)
    ├── Chapter 1 — Unit I — Sylow theorems, solvable and nilpotent groups
    ├── Chapter 2 — Unit II — Rings, ideals, polynomial rings and unique factorisation domains
    ├── Chapter 3 — Unit III — Modules, submodules and modules over PIDs
    ├── Chapter 4 — Unit IV — Field extensions, algebraic and transcendental extensions
    ├── Chapter 5 — Unit V — Galois theory and solvability by radicals
    ├── CSIR PYQ — Unit I — Sylow theorems, solvable and nilpotent groups
    ├── CSIR PYQ — Unit II — Rings, ideals, polynomial rings and UFD
    ├── CSIR PYQ — Unit III — Modules, submodules and modules over PIDs
    ├── CSIR PYQ — Unit IV — Field extensions, algebraic and transcendental extensions
    └── CSIR PYQ — Unit V — Galois theory and solvability by radicals
```

### Quiz Configuration — CSIR NET Mock Test

To simulate CSIR NET Part B conditions:

| Setting | Value |
|---------|-------|
| Questions per quiz | 20–25 |
| Marks per question | 2 |
| Negative marking | −0.5 (set penalty = 0.25 × 2) |
| Time limit | 45–60 minutes |
| Shuffle questions | Yes |
| Shuffle answers | Yes |
| Feedback shown | After quiz closes (to avoid answer leakage) |

---

## Mathematical Notation

All questions use **LaTeX** rendered via MathJax in Moodle:
- Inline math: `\( ... \)`
- Display math: `\[ ... \]`
- Common symbols used: `\mathbb{Z}`, `\mathbb{Q}`, `\mathbb{R}`, `\mathbb{C}`, `\mathbb{F}`, `\mathrm{Gal}`, `\varphi`, `\zeta`, `\sigma`, `\omega`, `\trianglelefteq`, `\oplus`, `\otimes`

Ensure **MathJax** or **TeX notation filter** is enabled in your Moodle site:  
`Site Administration → Plugins → Filters → Manage filters → Enable MathJax`

---

## Marking Scheme Reference

### Series 1 — Chapter-wise Practice
| Component | Value |
|-----------|-------|
| Correct answer | +1.0 |
| Wrong answer | −0.333 (1/3 penalty) |
| Unattempted | 0 |

### Series 2 — CSIR NET PYQ Pattern
| Component | Value |
|-----------|-------|
| Correct answer | +2.0 |
| Wrong answer | −0.5 (1/4 penalty) |
| Unattempted | 0 |

This matches the official **CSIR NET Part B** marking scheme.

---

## About CSIR NET Mathematics — Algebra

The **Council of Scientific and Industrial Research National Eligibility Test (CSIR NET)** is conducted by NTA for Junior Research Fellowship and Lectureship in Mathematical Sciences.

- **Paper:** Mathematical Sciences
- **Part B:** 40 questions (MCQ), attempt all, 2 marks each, −0.5 penalty
- **Part C:** 60 questions (analytical), attempt 20, 4 marks each, −1 penalty
- **Algebra weightage:** Approximately 20–25% of Part B+C

The CSIR PYQ series in this bank covers the **Algebra** section comprehensively across all 5 units of the standard M.Sc. syllabus.

---

*Prepared for: Advanced Algebra (M.Sc. Mathematics) — CSIR NET Preparation*  
*Format: Moodle XML (compatible with Moodle 3.x and 4.x)*  
*Total questions: 135 CSIR PYQ MCQs + Chapter-wise practice sets*
