# CRISP Executive System Architecture

## Overview

CRISP (Concentration Risk in Supply Portfolio) is an AI-powered decision intelligence platform developed in Palantir Foundry to support Department of Defense contracting officers in identifying supplier concentration risk, evaluating acquisition strategies, and improving industrial base resilience.

The architecture demonstrates how public procurement data is transformed into actionable decision support while maintaining a human-in-the-loop acquisition process.

---

## Executive Architecture

![CRISP Executive Architecture](crisp_executive_architecture.png)

---

## Architecture Components

### 1. Data Layer

Public FPDS procurement data provides historical contract, vendor, and Product Service Code (PSC) information.

### 2. Data Processing & Ontology

Data is integrated, validated, and organized into operational business objects using the Foundry Ontology.

### 3. Risk Analytics

Analytics calculate vendor concentration using the Herfindahl–Hirschman Index (HHI), assess foreign exposure, and predict market entry using an XGBoost machine learning model.

### 4. Decision Intelligence

Workshop applications present insights through four operational workflows:

- Contract Overview
- PSC Analysis
- Contract Strategy
- Decision Inbox

### 5. Operational Execution

Contracting officers use AI-assisted recommendations to support acquisition planning while retaining full decision authority.

---

## Technologies

- Palantir Foundry
- Ontology
- Pipeline Builder
- Workshop
- AIP
- Python
- SQL
- XGBoost
