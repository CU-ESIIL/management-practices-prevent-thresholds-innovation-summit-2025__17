# Code & Analysis Assets

This page highlights the scripts and notebooks powering the Management Practices Prevent Thresholds prototype. Everything lives in the [`code/`](https://github.com/CU-ESIIL/management-practices-prevent-thresholds-innovation-summit-2025__17/tree/main/code) folder; start there if you want to contribute.

## Featured workflows
| File | Description | How to run |
|------|-------------|------------|
| [`prism_quicklook.py`](https://github.com/CU-ESIIL/management-practices-prevent-thresholds-innovation-summit-2025__17/blob/main/code/prism_quicklook.py) | Streams PRISM climate rasters via GDAL VSI, optionally crops to an AOI, and produces quick-look plots for anomaly inspection. | `python prism_quicklook.py` (see docstring for optional arguments or import the helper functions into notebooks). |
| [`fired_time_hull_panel.ipynb`](https://github.com/CU-ESIIL/management-practices-prevent-thresholds-innovation-summit-2025__17/blob/main/code/fired_time_hull_panel.ipynb) | Notebook with end-to-end workflow for detecting change points, assembling management indicators, and rendering dashboard prototype panels. | Open in JupyterLab (CyVerse or local) → run cells sequentially. Configure data paths in the first cell. |
| [`single_hull_demo.py`](https://github.com/CU-ESIIL/management-practices-prevent-thresholds-innovation-summit-2025__17/blob/main/code/single_hull_demo.py) | Minimal example that builds a vertical hull visualization for a single FIRED event, mirroring the main notebook without dependencies. | Requires `geopandas`, `matplotlib`, and `shapely`. Run `python single_hull_demo.py` after pointing it to a cleaned GeoDataFrame. |

## Documentation notes
- [`data_processing.md`](https://github.com/CU-ESIIL/management-practices-prevent-thresholds-innovation-summit-2025__17/blob/main/code/data_processing.md) captures ETL assumptions and CyVerse folder conventions.
- [`visualizations.md`](https://github.com/CU-ESIIL/management-practices-prevent-thresholds-innovation-summit-2025__17/blob/main/code/visualizations.md) describes design choices for dashboard components and alert messaging.
- [`data_analysis.md`](https://github.com/CU-ESIIL/management-practices-prevent-thresholds-innovation-summit-2025__17/blob/main/code/data_analysis.md) tracks exploratory analyses not yet integrated into the main notebook.

## Contributing guidelines
- Place new scripts/notebooks in `code/` and document required data paths at the top of the file.
- Prefer relative paths (e.g., `../data/processed/`) so others can reproduce your runs.
- Update this page whenever you add a major workflow so visitors can find it quickly.
