# Virtual plasmid curing and transformation

Simulation code and generated data supporting the study:

**A theoretical framework for virtual plasmid curing and transformation**

## Repository contents

- `data/` – sanitized plasmid promoter/copy-number input used by the simulations
- `notebooks/` – simulation notebooks for Simulations 1–6
- `results/` – generated summary and representative bootstrap results
- `requirements.txt` – Python package requirements
- `LICENSE` – MIT License

## Reproducibility

The simulations were implemented in Python. Each notebook contains the code required to reproduce the corresponding simulation analysis.

The notebooks read the shared input file:

`data/plasmid_feature_pairs.csv`

and write generated outputs to:

`results/`

The simulations use 100 simulation replicates and 200 parametric-bootstrap replicates for the representative bootstrap analysis.

## Data

The repository contains simulated data and a sanitized plasmid-feature input table used by the simulations. BioSample identifiers and unrelated empirical variables were removed from the public input table.

## Software requirements

Install the required Python packages with:

```bash
pip install -r requirements.txt
