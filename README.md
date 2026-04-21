# CS229: Machine Learning — Stanford

Personal study notes and Python implementations following Andrew Ng's CS229 course.

> **Goal:** Build deep, principled understanding of ML theory — not just formula recall, but the ability to derive and explain results from first principles.

---

## Topics Covered

| # | Topic | Notes | Code |
|---|-------|-------|------|
| 1 | Linear Regression — OLS, LMS, Normal Equation | ✅ | — |
| 2 | Probabilistic Interpretation of Least Squares | ✅ | — |
| 3 | Locally Weighted Linear Regression (LWR) | ✅ | — |
| 4 | Logistic Regression, Perceptron, Newton's Method | ✅ | — |
| 5 | Exponential Family & Generalized Linear Models | ✅ | — |
| 6 | Locally Weighted Logistic Regression | ✅ | ✅ |
| 7 | Generative Learning Algorithms | 🔄 | — |
| 8 | Support Vector Machines | 🔜 | — |
| 9 | Neural Networks | 🔜 | — |

✅ Done &nbsp; 🔄 In progress &nbsp; 🔜 Upcoming

---

## Problem Sets

### PS1 — Supervised Learning

**Q2 highlights:**
- Newton-Raphson optimisation with weighted regularised log-likelihood
- Gaussian kernel weighting: $w^{(i)} = \exp\!\left(-\frac{\|x - x^{(i)}\|^2}{2\tau^2}\right)$
- Decision boundary analysis across $\tau \in \{0.01, 0.05, 0.1, 0.5, 1.0, 5.0\}$

---

## Notes Style

Each topic note covers:
1. **Mathematical foundation** — derivations from first principles
2. **Geometric intuition** — what the math means visually
3. **Connection to other algorithms** — e.g. why logistic regression and linear regression share the same update rule structure

---

## Resources

| Resource | Link |
|----------|------|
| Lecture Notes | [CS229 Official Notes](https://cs229.stanford.edu/main_notes.pdf) |
| Original Repo | [SaaranshJain/andrew-ng](https://github.com/SaaranshJain/andrew-ng) |
| Course Page | [cs229.stanford.edu](https://cs229.stanford.edu) |

