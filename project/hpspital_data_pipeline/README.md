# Validation-Aware Hospital Data Pipeline

This project demonstrates a reproducible, multi-source health data pipeline designed to improve reliability and trust in hospital reporting workflows.

## What this shows
- Ingests common healthcare data formats (CSV, JSON API, HTML table)
- Applies standardized cleaning and reshaping
- Runs explicit validation checks (missingness, duplicates, type coercion, logical checks)
- Surfaces potential outliers (IQR-based) for review rather than automatically deleting them
- Produces stakeholder-friendly visual summaries as a final quality check

## Why it matters (research framing)
Hospital decisions depend on timely, consistent data. Manual preparation can introduce undocumented logic and silent errors. This pipeline highlights validation-aware design principles that improve transparency, traceability, and audit readiness.

## Files
- `Hospital Data Pipeline Report.pdf` — concise technical report
- `Hospital Pipeline Project.ipynb` — end-to-end, rerunnable notebook

## How to run (quick)
Open the notebook and run cells top-to-bottom. All steps are documented in-line.
