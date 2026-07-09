# CRISP – Concentration Risk in Supply Portfolio

## Overview

**CRISP (Concentration Risk in Supply Portfolio)** is an AI-powered decision intelligence platform developed in **Palantir Foundry** as part of the **Palantir American Tech Fellowship**. It enables Department of Defense contracting officers to identify vendor concentration risk, evaluate acquisition strategies, and strengthen industrial base resilience at the Product and Service Code (PSC) level.

By integrating procurement data, ontology-driven modeling, machine learning, and AI-assisted recommendations into a unified operational workflow, CRISP helps acquisition professionals transition from reactive contract management to proactive industrial base risk management.

---

## Problem Statement

Existing procurement systems provide visibility into individual contracts but do not measure supplier concentration at the PSC level, where acquisition risk becomes apparent. As a result, contracting officers may unknowingly re-award contracts in highly concentrated markets, reducing competition, increasing supply chain vulnerability, and limiting strategic sourcing options.

CRISP addresses this gap by shifting analysis from individual contracts to the PSC level, enabling earlier identification of concentration risk and supporting more informed acquisition decisions.

---

## Core Features

- Contract expiration monitoring
- PSC-level concentration analysis
- DOJ Herfindahl-Hirschman Index (HHI) risk assessment
- Foreign vendor exposure analysis
- XGBoost market entry prediction
- AI-assisted acquisition recommendations using AIP
- Mitigation strategy simulation
- End-to-end acquisition decision workflow

---

## Results

- Analyzed **27,000+ FPDS contract records** spanning **FY2020–FY2025**
- Calculated PSC-level vendor concentration using the DOJ Herfindahl-Hirschman Index (HHI)
- Developed an XGBoost model to estimate the likelihood of new vendor market entry
- Built an AI-assisted decision intelligence platform that guides contracting officers from contract expiration monitoring through acquisition strategy and execution

> **Note:** The repository showcases the project architecture, methodology, and implementation approach. Proprietary Palantir assets, ontology definitions, pipelines, and sensitive implementation details have been intentionally excluded.

---

## Technologies Used

- Palantir Foundry
- Workshop
- Ontology
- Pipeline Builder
- Artificial Intelligence Platform (AIP)
- Python
- SQL
- XGBoost

---

## Operational Workflow

1. **Contract Overview** – Monitor expiring contracts requiring acquisition review.
2. **PSC Analysis** – Evaluate market concentration, vendor exposure, and competitive landscape.
3. **Contract Strategy** – Simulate mitigation strategies and assess acquisition tradeoffs.
4. **Decision Inbox** – Execute acquisition workflows and AI-assisted market research recommendations.

---

## Repository Contents

This repository documents the architecture, analytics, and implementation approach used to build CRISP. It includes:

- Solution architecture
- Application screenshots
- Technical documentation
- Sample Python analytics
- Sample SQL queries
- Methodology documentation
- Public sample datasets

---

## Future Enhancements

- Historical PSC concentration trend analysis
- Additional predictive risk models
- Expanded acquisition strategy simulations
- Enhanced industrial base monitoring
- Additional AI-assisted acquisition workflows
