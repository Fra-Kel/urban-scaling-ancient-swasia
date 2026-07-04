# Urban scaling in Ancient Southwest Asia

Reproducibility notebook for Chelazzi and Lawrence (2026), "The emergence of urban scaling in Ancient Southwest Asia" (PLOS ONE).

## Run the notebook online

Click the badge below to launch the notebook in your browser (no installation required):

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Fra-Kel/urban-scaling-ancient-swasia/main)

Once Binder has built the environment, open `reproducibility_notebook.ipynb` and select **Run All** to reproduce all tables and figures.

## Contents

- `reproducibility_notebook.ipynb` — executable notebook (main text + Supplementary Material)
- `dataset.csv` — the dataset (comma-separated, Latin-1 encoded)
- `install.R` — R packages required (read by Binder)
- `runtime.txt` — R version (read by Binder)

The `dataset.csv` provided here contains 1,888 records; the notebook applies a filter (keeping records with a valid `TotalArea` and `TotalAreaHouse`) to obtain the analytical sample of 1,852 buildings from 80 sites reported in the paper.

## Permanent archive (Zenodo)

This repository is the executable environment used by Binder. The permanent, citable deposit — which also includes the two full R scripts alongside the dataset and this notebook — is archived on Zenodo with a DOI that always resolves to the latest version:

**https://doi.org/10.5281/zenodo.20172243**

## License

- **Dataset:** Creative Commons Attribution 4.0 International (CC-BY 4.0)
- **Code (notebook and scripts):** MIT License

## Citation

If you use this notebook, dataset, or scripts, please cite both the paper and the archived deposit:

Chelazzi, F. and Lawrence, D. (2026). The emergence of urban scaling in Ancient Southwest Asia. *PLOS ONE* [DOI when published].

Chelazzi, F. and Lawrence, D. (2026). Dataset, R scripts, and reproducibility notebook for: The emergence of urban scaling in Ancient Southwest Asia [Dataset]. *Zenodo*. https://doi.org/10.5281/zenodo.20172243
