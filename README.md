# Building a Linear Regression Model for Number of Housing Units

This repository contains code that merges three different data sources: [Global Building Atlas](https://sat-io.earthengine.app/view/gba) building footprints, [California parcel data](https://egis-lacounty.hub.arcgis.com/documents/baaf8251bfb94d3984fb58cb5fd93258/about), and individual household data provided through the capstone client (referred to here as "Zillow data"). It then uses available data on number of housing units to create a linear regression that predicts this information for observations for where it is missing.

## Repository Contents
```
── README.md
├── images
│   └── labeled_tiles.png
├── parquets_merge.ipynb
├── py_scripts
│   ├── unit_regression.py
│   └── unit_regression_claude.py
├── sofia_troubleshooting
│   ├── troubleshooting_unit_regression_sdge.ipynb
│   └── troubleshooting_unit_regression_ventura.ipynb
└── smallscale_regression
    ├── building_function.ipynb
    ├── parcel_exploration.ipynb
    ├── regression_draft.ipynb
    ├── regression_prep.ipynb
    ├── unit_regression_v1_la.ipynb
    ├── unit_regression_v2_sd.ipynb
    ├── unit_regression_v3_pge.ipynb
    ├── unit_regression_v4_ventura.ipynb
    └── unit_regression_v5_marin.ipynb
```

### Folder description
**images**: Contains a single image with labeled parquet parcels for `parquets_merge.ipynb` notebook.

**py_scripts**: .py scripts that were used to run unit regression on a smaller scale.

**sofia_troubleshooting**: Some troubleshooting code for honing unit regression pipeline (completed by Sofia Rodas – hence the name)

**smallscale_regression**: Multiple notebooks running different iterations of unit regression on different areas of California.

## Contributors
- [Sofia Sarak](https://github.com/sofiasarak)
- [Sofia Rodas](https://github.com/sofiiir)
- [Zach Loo](https://github.com/zachyyy700)

The analysis is part of a larger capstone project for the [Master of Environmental Data Science program](https://bren.ucsb.edu/masters-programs/master-environmental-data-science) at the Bren School of Environmental Science & Management. More information on the project can be found on the [Bren website](https://bren.ucsb.edu/projects/power-lines-and-people-mapping-how-distribution-grid-constraints-shape-resilient-and).
