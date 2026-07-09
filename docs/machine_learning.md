# Machine Learning

## Objective

CRISP uses machine learning to estimate the likelihood that a Product Service Code (PSC) market will attract new vendors. The objective is to support contracting officers in identifying markets where competition is unlikely to improve without acquisition intervention.

---

## Business Problem

Highly concentrated supplier markets present elevated acquisition risk. Historical procurement patterns can be used to estimate whether new vendors are likely to enter a market.

---

## Model

The prototype uses an XGBoost classification model trained on historical procurement data.

The model predicts the probability of future vendor entry into a PSC market.

---

## Features

The prototype evaluates several market characteristics, including:

- Herfindahl–Hirschman Index (HHI)
- Vendor count
- Total obligations
- Contract activity
- Historical market trends

---

## Results

The prototype achieved:

- ROC-AUC: **0.71**

The most influential features included vendor count and market concentration (HHI).

---

## Human-in-the-Loop

Model predictions support acquisition planning but do not replace contracting officer judgment. Final acquisition decisions remain under human authority.

---

## Technology Stack

- Python
- XGBoost
- Palantir Foundry
- SQL
