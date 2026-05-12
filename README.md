# Building a Linear Regression Model for Number of Housing Units

This repository contains code that merges three different data sources: [Global Building Atlas](https://sat-io.earthengine.app/view/gba) building footprints, [California parcel data](https://egis-lacounty.hub.arcgis.com/documents/baaf8251bfb94d3984fb58cb5fd93258/about), and individual household data provided through the capstone client (referred to here as "Zillow data"). It then uses available data on number of housing units to create a linear regression that predicts this information for observations for where it is missing.

## Repository Contents and Description
```
├── images
│   └── labeled_tiles.png
├── multi_unit_regression.ipynb
├── parquets_merge.ipynb
├── regression_prep.ipynb
├── validate_units.ipynb
└── visualization.ipynb
```

**images**: Contains a single image with labeled parquet parcels for `parquets_merge.ipynb` notebook.

**multi_unit_regression.ipynb**: Final unit regression pipeline. Requires building footprints, residential home points, and parcel data to run.

**parquets_merge.ipynb**: Merges all of the Global Building Atlas tiles that cover California into file.

**regression_prep.ipynb**: Preliminary exploration and a scatterplot showing building volume v. number of residential units.

**validate_units.ipynb**: Exploration of multi_unit_regression.ipynb results.

**visualization.ipynb**: Currently incomplete (accidentally deleted). Will contain exploratory visualizations of multi_unit_regression.ipynb results and compare them to the original Zillow data.


## Contributors
- [Sofia Sarak](https://github.com/sofiasarak)
- [Sofia Rodas](https://github.com/sofiiir)
- [Zach Loo](https://github.com/zachyyy700)

The analysis is part of a larger capstone project for the [Master of Environmental Data Science program](https://bren.ucsb.edu/masters-programs/master-environmental-data-science) at the Bren School of Environmental Science & Management. More information on the project can be found on the [Bren website](https://bren.ucsb.edu/projects/power-lines-and-people-mapping-how-distribution-grid-constraints-shape-resilient-and).
