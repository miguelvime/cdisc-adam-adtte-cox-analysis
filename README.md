# End-to-End Clinical Data Pipeline & Inferential Analysis

An implementation of a clinical trial data pipeline, from raw simulated data to regulatory standard conformance (CDISC) and inferential survival analysis.

## Project Overview
- **Objective:** Evaluate the efficacy of mantiamyloid monoclonal antibody medication vs. Placebo in Time-to-Event endpoints.
- **Data Engineering:** Mapped raw clinical data into CDISC SDTM and derived ADaM ADTTE datasets using **R pharmaverse** (Admiral package).
- **Statistical Analysis:** Executed semi-parametric Cox Proportional Hazards models and Kaplan-Meier survival curves to estimate Hazard Ratios (HR).
