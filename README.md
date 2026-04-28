# Climate Variability and Drought Effects on Cattle Stocking Decisions

## About

This repository contains replication code and data for a study examining how drought and extreme heat affect cattle stocking rates across U.S. pasture systems (1982–2022), with climate projections through 2099 under RCP 4.5 and RCP 8.5.

---

## Repository Structure

```
DWFI_drought/
├── code/
│   ├── 1_Data_collection_v4.qmd         # Collects and processes all raw data inputs:
│   │                                    # pastureland, beef inventory, hay stocks,
│   │                                    # cattle weights, PRISM climate, CanESM5
│   │                                    # projections, USDM drought, and PDSI data
│   │
│   ├── 2_Analysis_v4.qmd                # Constructs stocking rates, estimates the
│   │                                    # fixed-effects panel regression, runs
│   │                                    # robustness checks, and generates projected
│   │                                    # stocking rates across 10 ensemble realizations
│   │
│   ├── 3_Make_tables_and_figures_v4.qmd # Produces all tables and figures in the paper
│   │
│   └── 4_Hay_Projections_v4.qmd         # Projects state-level hay stocks under
│                                        # RCP 4.5 and RCP 8.5 for use in projections
│
├── data/                                # Raw and processed data files
└── manuscript/                          # Current manuscript draft
```

---


## Data Access

Large raw files (PRISM grids, CanESM5 NetCDFs) are not stored in this repository due to size. Sources:

| Dataset | URL |
|---------|-----|
| PRISM historical climate | https://prism.oregonstate.edu |
| CanESM5 projections (RCP 4.5 / 8.5) | https://esgf-node.llnl.gov |
| USDA Census of Agriculture | https://www.nass.usda.gov/AgCensus |
| USDA NASS Quick Stats | https://quickstats.nass.usda.gov |
| U.S. Drought Monitor | https://droughtmonitor.unl.edu |
| TerraClimate (PDSI) | https://www.climatologylab.org/terraclimate.html |


---

## Contact

**Shara Akat** | University of Nebraska–Lincoln | GitHub: [@SharaAkat0828](https://github.com/SharaAkat0828)
