
# psych-ra-samples

Research-ops + clean-data examples (REDCap/Qualtrics → tidy data → analysis in R) and selected writing.
This repo is designed so a PI can skim the structure, open a notebook, and see reproducible outputs fast.

## Contents
- `/code/` — R Markdown notebooks (data cleaning, REDCap/Qualtrics workflow, prereg/power)
- `/data/` — mock/simulated or de-identified sample datasets for demos
- `/outputs/` — rendered analysis artifacts (HTML/CSV/figures) and writing samples
  - Policy Analysis Memorandum (working paper): “Minimum Wage & Unemployment” (`outputs/minimum_wage_unemployment_analysis_Siegler.docx`)
- `/certs/` — certificate and lisences
- `/thesis/` — published thesis PDF and a short README

## Open materials (quick links)
- **Data Cleaning & Descriptives** — `code/01_data_cleaning_descriptives.Rmd` → renders to `outputs/01_data_cleaning_descriptives.html`
- **REDCap/Qualtrics Workflow** — `code/02_redcap_qualtrics_workflow.Rmd`
- **Pre‑Registration & Power (demo)** — `code/03_pre_reg_power_analysis.Rmd`
- **Policy analysis report** — `outputs/minimum_wage_unemployment_analysis_Siegler.docx`

## Compliance & data handling
- **CITI**: Human Subjects (SBE) and GCP completed.
- **Data**: Share **de-identified** or **synthetic** data only. Do not upload PHI. Follow IRB/HIPAA and sponsor policies.
- **Reproducibility**: Keep codebooks and data dictionaries in the repo; avoid committing raw PHI or restricted data.

## Notes for reviewers
- The focus here is **study ops + tidy data**: consent/scheduling → REDCap/Qualtrics setup → de-identified exports → analysis-ready tables.
- If you want a specific demo (e.g., EMA/ESM scheduling, stratified randomization, or QA dashboards), open an issue and I’ll add a notebook.
