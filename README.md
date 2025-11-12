## Replication, Environment, and Data Access (BPLIM)

This repository contains the statistical code (R scripts), data-construction routines, and documentation required to reproduce the tables and figures used in the paper. The code is designed to run inside the Banco de Portugal Microdata Research Laboratory (BPLIM) secure environment.

### Quick start (inside BPLIM)
1. Clone this repository to your BPLIM workspace.
2. Copy `config/config.example.R` to `config/config.R` and set the local BPLIM paths to the required datasets.
3. In R, run:
   ```r
   source("config/config.R")
   source("code/psm/PSM_only_AICEP_panels_clean.R")
# the_effects_of_EU-funded_innovation_grants_on_firm_performance
Fully reproducible code and materials for the paper “EU-funded innovation grants and firm outcomes: evidence from Portugal (PT2020)”. It implements the applicant-based, interaction-weighted staggered DiD design with pre-treatment PSM, and produces all tables/figures reported in the paper.
