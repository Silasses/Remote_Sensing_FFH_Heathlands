# Remote Sensing of Dry Heathlands (FFH Habitat 4030)

This repository provides an **R-based workflow** for the remote sensing analysis of dry heathland habitats (*Calluna vulgaris*, FFH type 4030).  
The workflow mosaics **orthophotos** and **nDOM tiles**, calculates **NDVI**, applies an **unsupervised k-means classification**, and derives structural phases (pioneer, development, mature, degenerate) as well as open ground fractions.  

All paths are **relative**, so the pipeline runs reproducibly on any system with the required input data.

---

## 🚀 Project structure
your-repo/
├─ data/
│ ├─ orthophotos/ # input orthophoto tiles (.jp2)
│ ├─ ndom/ # input nDOM tiles (.tif)
│ └─ vector/ # vector data & attribute tables
│ ├─ Trocken_Heiden_Senne.gpkg
│ └─ lrt_data_senne4030.xlsx
├─ processed/ # automatically created for outputs
├─ R/
│ └─ 01_run.R # main script
└─ README.md
