# The Effects of EU-Funded Innovation Grants on Firm Performance

This repository contains the code and documentation for the paper:

**Barbosa, Paulo Henrique**  
*The Effects of EU-Funded Innovation Grants on Firm Performance*

The project evaluates the impact of EU-funded innovation grants in Portugal under the **PT2020** framework. The empirical strategy combines an **interaction-weighted event-study / staggered difference-in-differences design** with an **applicant-based counterfactual** and **propensity-score matching**.

The repository is intended to make the empirical workflow transparent and to facilitate replication **within the authorized data environment**.

---

## What this repository reproduces

The code reproduces the main empirical outputs of the paper/chapter, including:

- descriptive statistics for treated firms, rejected applicants, and never-applicants
- baseline treatment-effect estimates
- applicant-based event-study estimates
- propensity-score-matched estimates
- tables and figures reported in the paper

In particular, the workflow is designed to generate the main outputs for the innovation-grants essay / chapter of the thesis.

---

## Data access and replication limits

This project relies on **restricted-access confidential microdata** and is designed to run inside the **Banco de Portugal Microdata Research Laboratory (BPLIM)** secure environment.

Because of that:

- full replication is only possible for authorized users with access to the underlying data
- external users can still inspect the code, identification strategy, and project structure
- no confidential data are included in this repository

Please do **not** expect the code to run end-to-end outside the authorized research environment unless equivalent data access and file paths are available.

---

## Repository structure

A typical workflow uses the following components:

- `README.md` — project overview and setup instructions
- `config/` — local configuration files and path definitions
- `code/` — main analysis script(s)
- `outputs/` — exported tables, figures, and intermediate results created during execution

Adjust the folder names below if your local version differs.

---

## Requirements

The analysis is written in **R**.

You will need:

- R
- the packages used by the analysis scripts
- access to the restricted input datasets
- a local configuration file with valid paths

For reproducibility, it is a good idea to record:

- R version
- package versions
- execution date
- secure environment / machine details where relevant

---

## Setup

### 1. Clone the repository

```bash
git clone https://github.com/paulofbarbosa5/the_effects_of_EU-funded_innovation_grants_on_firm_performance.git
cd the_effects_of_EU-funded_innovation_grants_on_firm_performance
