# MeLiDos Project Data Hub

This repository provides a project-level overview of the MeLiDos dataset ecosystem, with a focus on the site-specific personal light exposure datasets and their citation metadata.

## Scope

The MeLiDos project provides harmonized datasets from multiple field sites measuring personal light exposure in naturalistic settings. Across datasets, the records include wearable-light-derived metrics relevant to visual and non-visual (e.g., circadian / melanopic) light exposure analyses.

This hub README is intended to:

- summarize the dataset repositories in one place,
- provide citation-ready references for each dataset,
- document key per-dataset details (site, version, DOI, file size, and lead institutions), and
- point to the companion **melidosData** repository for downstream data access workflows.

## Dataset repositories (MeLiDosProject)

### 1) `AkuffoEtAl_Dataset_2025` (Kumasi, Ghana)

- **Repository:** https://github.com/MeLiDosProject/AkuffoEtAl_Dataset_2025
- **Zenodo DOI (v1.0.1):** https://doi.org/10.5281/zenodo.16638654
- **Zenodo DOI (v1.0.0):** https://doi.org/10.5281/zenodo.15576732
- **Version notes:** v1.0.1 supersedes v1.0.0
- **Dataset package size:** ~48.7 MB (v1.0.1), ~45.0 MB (v1.0.0)
- **Collection site:** Kumasi, Ghana
- **Collection institution:** Kwame Nkrumah University of Science and Technology (KNUST)
- **Citation (dataset creators):** Akuffo, K.O.; Agbeshie, G.K.; Zauner, J.; Spitschan, M.

### 2) `BaezaEtAl_Dataset_2025` (Madrid, Spain)

- **Repository:** https://github.com/MeLiDosProject/BaezaEtAl_Dataset_2025
- **Zenodo DOI (v1.0.1):** https://doi.org/10.5281/zenodo.17303713
- **Dataset package size:** ~82.6 MB
- **Collection site:** Madrid, Spain
- **Collection institution:** Fundación Universitaria CEU San Pablo (FUSP-CEU)
- **Citation (dataset creators):** Baeza Moyano, D.; Pérez Gutiérrez, M.C.; Cantarero García, G.; González Lezcano, R.A.; Melero Tur, S.; Zauner, J.; Spitschan, M.

### 3) `GuidolinEtAl_Dataset_2025` (Tuebingen, Germany)

- **Repository:** https://github.com/MeLiDosProject/GuidolinEtAl_Dataset_2025
- **Zenodo DOI (v1.0.0):** https://doi.org/10.5281/zenodo.16895307
- **Dataset package size:** ~165.4 MB
- **Collection site:** Tuebingen, Germany
- **Collection institution:** Max Planck Institute for Biological Cybernetics (MPI-KYB)
- **Protocol note:** legacy/pre-protocol dataset used to shape later MeLiDos protocolized datasets
- **Citation (dataset creators):** Guidolin, C.; Zauner, J.; Spitschan, M.

### 4) `HildenEtAl_Dataset_2025` (Munich, Germany)

- **Repository:** https://github.com/MeLiDosProject/HildenEtAl_Dataset_2025
- **Zenodo DOI (v1.0.1):** https://doi.org/10.5281/zenodo.17337841
- **Dataset package size:** ~41.0 MB
- **Collection site:** Munich, Germany
- **Collection institution:** Technical University of Munich (TUM)
- **Citation (dataset creators):** Hilden, S.; Lee, S.; Zauner, J.; Spitschan, M.


### 5) `NilssonEtAl_Dataset_2025` (Gothenburg, Sweden)

- **Repository:** https://github.com/MeLiDosProject/NilssonEtAl_Dataset_2025
- **Zenodo DOI (latest):** not yet documented in this hub
- **Version notes:** release metadata pending synchronization into this hub
- **Dataset package size:** not yet documented in this hub
- **Collection site:** Gothenburg, Sweden
- **Collection institution:** not yet documented in this hub
- **Citation (dataset creators):** Nilsson, M.; Zauner, J.; Spitschan, M.

### 6) `AertsEtAl_Dataset_2025` (Delft, The Netherlands)

- **Repository:** https://github.com/MeLiDosProject/AertsEtAl_Dataset_2025
- **Zenodo DOI (v1.0.0):** https://doi.org/10.5281/zenodo.17979895
- **Version notes:** initial release currently listed in this hub
- **Dataset package size:** not yet documented in this hub
- **Collection site:** Delft, The Netherlands
- **Collection institution:** not yet documented in this hub
- **Citation (dataset creators):** Aerts, S.; Jansen, A.; Hogervorst, N.; Boesten, D.; Bolte, J.; Zauner, J.; Spitschan, M.

### 7) `BroszioEtAl_Dataset_2025` (Dortmund, Germany)

- **Repository:** https://github.com/MeLiDosProject/BroszioEtAl_Dataset_2025
- **Zenodo DOI (v1.0.0):** https://doi.org/10.5281/zenodo.18244467
- **Version notes:** initial release currently listed in this hub
- **Dataset package size:** not yet documented in this hub
- **Collection site:** Dortmund, Germany
- **Collection institution:** not yet documented in this hub
- **Citation (dataset creators):** Broszio, K.; Zauner, J.; Spitschan, M.

### 8) `SanchoSalasEtAl_Dataset_2025` (San Pedro, San José, Costa Rica)

- **Repository:** https://github.com/MeLiDosProject/SanchoSalasEtAl_Dataset_2025
- **Zenodo DOI (latest):** not yet documented in this hub
- **Version notes:** release metadata pending synchronization into this hub
- **Dataset package size:** not yet documented in this hub
- **Collection site:** San Pedro, San José, Costa Rica
- **Collection institution:** not yet documented in this hub
- **Citation (dataset creators):** Sancho-Salas, A.; von-Breymann, H.; Zauner, J.; Spitschan, M.

### 9) `DidikogluEtAl_Dataset_2025` (Izmir, Türkiye)

- **Repository:** https://github.com/MeLiDosProject/DidikogluEtAl_Dataset_2025
- **Zenodo DOI (v1.0.0):** https://doi.org/10.5281/zenodo.16568110
- **Version notes:** initial release currently listed in this hub
- **Dataset package size:** not yet documented in this hub
- **Collection site:** Izmir, Türkiye
- **Collection institution:** not yet documented in this hub
- **Citation (dataset creators):** Didikoglu, A.; Akgun, S.G.; Aydin, S.N.; Kayar, Z.; Zauner, J.; Spitschan, M.

## Companion repository: `melidosData`

The **melidosData** repository should be treated as the companion access/integration layer for the site-level MeLiDos datasets listed above. In project workflows, it is the recommended entry point for reproducible dataset loading, harmonization, and downstream analysis pipelines.

> Note: If the melidosData repository introduces additional dataset releases or citation contributors, this README and `CITATION.cff` should be updated accordingly.

## Consolidated citation guidance

Please cite both:

1. the specific site-level dataset(s) you used (from the list above), and
2. this project-level repository for cross-dataset aggregation context.

All contributor names merged across currently documented dataset citation metadata are included in this repository's `CITATION.cff`.
