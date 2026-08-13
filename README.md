# GLASS
Source notebook and reproducibility materials for GLASS, a gated link-aware SGP4 correction method for GNSS-degraded tactical LEO-NTN link planning.


## How to Run

1. Open `GLASS_MILCOM_ARTIFACT.ipynb` in Google Colab.

2. Run the cells from top to bottom.

3. When prompted, provide the required data-access credentials for the external orbit/TLE sources.

4. The notebook will train/evaluate GLASS and regenerate the result files and figures.

## Notes

- The notebook was prepared for reproducing the GLASS MILCOM experiment workflow.
- Small numerical differences may occur across reruns because the workflow includes model training and external data retrieval.
- The main outputs include JSON/CSV result summaries and paper-style figures.
