# Notes on Conformal Prediction Cheat Sheet

This document contains additional details, future updates, and extended discussions related to the Conformal Prediction Cheat Sheet.

## 📝 Planned Improvements

- [x] Add Jacknife+
- [ ] Add CV+
- [ ] Add Classification Cheat Sheet
- [ ] Improve layout and readability of the PDF
- [ ] Expand on use cases and implementation examples

## 📊 Table of Conformal Prediction Methods

| Method                              | Classifier | Regressor | Reference |
|-------------------------------------|------------|-----------|-----------|
| **Full CP**       | Yes        | Yes       | Vovk et al. (2005) - *Algorithmic Learning in a Random World* |
| **Inductive (Split) CP** | Yes | Yes | Papadopoulos et al. (2002) - *Inductive Confidence Machines for Regression* |
| **Cross CP**      | Yes        | Yes       | Vovk (2015) - *Cross-Conformal Predictors* |
| **Mondrian CP**   | Yes        | Yes       | Vovk et al. (2003) - *Mondrian Confidence Machines* |
| **Conformalized Quantile Regression**   | No        | Yes       | Romano et al. (2019) - *Conformalized Quantile Regression* |
| **Venn-Abers Predictors**           | Yes        | No       | Vovk & Petej (2012) - *Venn–Abers Predictors* |
| **Jackknife+**    | Yes        | Yes       | Barber & Candès (2021) - *Venn–Abers Predictors* |

**Table 1**: Types of Conformal Prediction for Classification and Regression  

## 📌 Discussion & Open Questions

- Should we add a comparison of computational costs for each method?
- How can we improve clarity without making the cheat sheet too long?
- Are there additional references worth including?
