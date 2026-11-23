# Company_Future_Prediction_ML
The objective of this project is to use open data (found in annuaires-entreprises.data.gouv.fr) to predict if a compagny will succeed or go bankrupt in its early stages. This will allow us to know the decinding criterias that make a start up successful and use this in our future carreer to maybe launch a start up someday.

## Data Sources

This project uses public open datasets published by the French government:

- **Detailed Financial Statements (`export-detail-bilan.parquet`):** [Données financières détaillées des entreprises (format parquet)](https://www.data.gouv.fr/datasets/donnees-financieres-detaillees-des-entreprises-format-parquet) on `data.gouv.fr` (Licence Ouverte / Open Licence 2.0).
- **SIRENE Register:** [Base Sirene des entreprises et de leurs établissements](https://www.data.gouv.fr/datasets/base-sirene-des-entreprises-et-de-leurs-etablissements-siren-siret) on `data.gouv.fr`.
- **Annuaire des Entreprises Data:** [Données des entreprises utilisées dans l'Annuaire des Entreprises](https://www.data.gouv.fr/datasets/donnees-des-entreprises-utilisees-dans-lannuaire-des-entreprises) on `data.gouv.fr`.

> **Note:** Raw `.parquet` / `.zip` / `.csv` data files are not committed to this repository due to file size; download them from the links above and place them in your local data directory before running the notebooks.
