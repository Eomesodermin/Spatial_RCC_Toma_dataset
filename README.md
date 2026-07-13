# Spatial RCC — spatial transcriptomics analysis

Preprocessing and analysis of a **renal cell carcinoma (RCC) spatial transcriptomics** dataset,
mapping immune and tumour compartments in tissue context.

## Analysis
- `scripts/01_Spatial_RCC_dataset_preprocessing.Rmd` — spatial data import, QC, normalisation, and spatial clustering

## Data
Raw/processed spatial data is kept outside version control; no patient-identifying information is
included in this repository.

---
Analysis by **Dillon Corvino** · [GitHub](https://github.com/Eomesodermin) · [dilloncorvino.com](https://dilloncorvino.com)

## Environment

Built in **R** with a Seurat-based single-cell stack — key packages: `Seurat`, `SeuratDisk`, `scCustomize`, `dplyr`, `ggplot2`, `future`, plus my helper package [`r-utility-functions`](https://github.com/Eomesodermin/r-utility-functions).

No pinned `renv.lock` is committed; the packages listed above are the required dependencies.
