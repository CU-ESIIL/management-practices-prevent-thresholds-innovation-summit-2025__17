# Data & Access

Key datasets supporting the threshold prevention dashboard. Store working copies in our CyVerse community folder so everyone can reuse them.

## Primary sources
| Dataset | Description | Access notes |
|---------|-------------|--------------|
| GridMET soil moisture anomalies | Daily gridded soil moisture anomalies used for early warning signals. | Download via `code/prism_quicklook.py` or Earth Engine; cached GeoTIFFs live in CyVerse `Group_17/data/raw/gridmet/`. |
| Management practice log | Partner-provided CSV capturing grazing rotations, rest periods, and riparian actions. | Sensitive contact info removed. Latest cleaned file: `Group_17/data/processed/management_log_clean.csv`. |
| Landsat NDVI composites | 30 m vegetation vigor metrics generated in Earth Engine. | Export to CyVerse `Group_17/data/raw/landsat/`. Use Earth Engine script shared in the notebook to refresh. |

## Supporting references
- [US Drought Monitor archive](https://droughtmonitor.unl.edu/Data/DataTables.aspx) for contextual drought status.
- [PRISM climate data portal](https://prism.oregonstate.edu/) for additional temperature and precipitation fields.
- [Western Water Conservancy practice playbook](https://example.org) *(internal PDF — see Slack pin).* 

## Data management reminders
- Always upload shared datasets to the CyVerse community folder before referencing them in notebooks.
- Document any preprocessing steps in `code/data_processing.md` so we can reproduce outputs.
- When using external services (Earth Engine, PRISM), capture the query parameters in commit messages or README snippets.
