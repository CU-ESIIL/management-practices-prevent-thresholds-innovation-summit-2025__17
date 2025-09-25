# Identifying linked disturbances and associated management intervenetions to prevent tipping points

<!-- =========================================================
HERO (Swap hero.jpg, title, strapline, and the three links)
========================================================= -->

**Importance:** Using the ICS database we are identifying whether ecological disturbances have overlapped in the U.S. and if there are intervention straetegies that can mitigate the impacts of linked disturabnce.

> **About this site:** This public log captures our rapid work at the Innovation Summit. Update it directly in your browser (open a file → pencil icon → Commit changes) so teammates and partners can follow along.

<!-- 

## How to use this page (for the team)
- **Edit this file:** `docs/index.md` → ✎ → change text → **Commit changes**.
- **Add images:** upload to `docs/assets/` and reference like `assets/your_file.png`.
- Keep **text short** and **visuals first**. Think “slide captions,” not essays.

-->

## Day 1 — Define & Explore
**Focus:** Exploring where the relevance of linked disturbance

### Our product 📣
- A synthesis manuscript and high level dataset of forest management actions (maybe a map or something)

### Our question(s) 📣
- What management actions take place after drought, windstorm, fire, and insect/path to prevent future wildfires?
  - ie. how are managers purposefully or inadvertently breaking disturbance links in order to prevent future catastrophic disturbances and tipping points?

### Hypotheses / intentions 📣
- Forest management interventions implemented within 1-3 years following drought, windstorm, or insect/pathogen disturbances significantly reduce the probability of subsequent catastrophic wildfire events, effectively breaking disturbance-linkage cascades that could lead to ecosystem tipping points.
- Proactive management following non-fire disturbances reduces total fire suppression costs compared to reactive fire management strategies.

### Why this matters (the “upshot”) 📣
- Disturbances can facilitate others. If disturbances are becoming more common with climate change, we might be able to intervene once a disturbance occurs to prevent further loss of ecosystem and life.

### Inspirations (papers, datasets, tools)
**Publication:**
- Dataset portal: St. Denis, L.A., Mietkiewicz, N.P., Short, K.C., Buckland, M. and Balch, J.K., 2020. All-hazards dataset mined from the US National Incident Management System 1999–2014. Scientific data, 7(1), p.64.

---

## Day 2 — Data & Methods
*Focus: Compiling incident reports within 20 km area to identify potential linked and compound effects

### Data sources we’re exploring 📣
<!-- EDIT: Link each source; add size/notes if relevant. -->
1. [US_National_Incident_Management_System](https://figshare.com/articles/dataset/All-hazards_dataset_mined_from_the_US_National_Incident_Management_System_1999-2020/19858927/3)
    - Fire incident data
1. [USFS Aerial Detection Survey](https://www.fs.usda.gov/science-technology/data-tools-products/fhp-mapping-reporting/detection-surveys)
    - Aerial survey of the health of treed areas affected by insects and diseases
1. [ECMWF Reanalysis v5 (ERA5)](https://www.ecmwf.int/en/forecasts/dataset/ecmwf-reanalysis-v5)
    - Percipitation (for drought calculation)
1. [Blowdown data of wind events](https://landfire.gov/disturbance/annualdisturbance)

### Methods / technologies we’re testing 📣
- Compiling data via R
- Mapping overlapping incidents throughout the US

### Challenges identified
- Data gaps / quality issues
- Method limitations / compute constraints
- Open questions we need to decide on

---

## Final Share Out — Insights & Sharing
*Focus: synthesis; highlight 2–3 visuals that tell the story; keep text crisp. Practice a 2-minute walkthrough of the homepage 📣: Why → Questions → Data/Methods → Findings → Next.*

### Findings at a glance 📣
<!-- EDIT: 2–4 bullets, each a headline in plain language with a number if possible. -->

- There are multiple disturbance events that greatly increase the likelihood of a future fire. 
- What types of actions may be effective in breaking the link between disturbances?
- Can preemptive action reduce the costs of fire resources in the context of multiple disturbances?

### Visuals
#### Map of overlapping incidents

![]()
*Visual 1.* .

<!-- EDIT: Swap visuals; prioritize clarity.

Incidents 
Diversity
Transitions

![]()
*Visual 1.* .

![Supporting panels for key insights](assets/hull_panels.png)
[Raw photo location: hull_panels.png](https://github.com/CU-ESIIL/management-practices-prevent-thresholds-innovation-summit-2025__17/blob/main/docs/assets/hull_panels.png)
*Visual 2.* Use a complementary panel, collage, or set of snapshots that reinforces supporting evidence.

![Complementary result figure placeholder](assets/main_result.png)
[Raw photo location: main_result.png](https://github.com/CU-ESIIL/management-practices-prevent-thresholds-innovation-summit-2025__17/blob/main/docs/assets/main_result.png)
*Visual 3.* Highlight an additional visual that captures a secondary insight or next step.
 
-->

### What’s next? 📣
- Immediate follow-ups
- What we would do with one more week/month
- Who should see this next

---

## Team
| Name | Role | Contact | 
|------|------|---------|
| Megan Oldfather | Researcher | moldfather@usgs.gov | 
| Max Stiefel | Researcher | maximilian.stiefel@kcl.ac.uk | 
| Cullen Molitor | Researcher | cmolitor@berkeley.edu | 
| Sam Reed | Researcher | reed0632@umn.edu | 
| Brian Miller | Researcher | bwmiller@usgs.gov | 
| Stefan Tangen | Researcher | stangen@usgs.gov | 
| Joan Dudney | Science Advisor | dudney@bren.ucsb.edu | 

---

## Storage

### Code
Keep shared scripts, notebooks, and utilities in the [`code/`](https://github.com/CU-ESIIL/management-practices-prevent-thresholds-innovation-summit-2025__17/tree/main/code) directory. Document how to run them in a README or within the files so teammates and visitors can reproduce your workflow.

### Documentation
Use the [`docs/`](https://github.com/CU-ESIIL/management-practices-prevent-thresholds-innovation-summit-2025__17/tree/main/docs) folder to publish project updates on this site. Longer internal notes can live in [`documentation/`](https://github.com/CU-ESIIL/management-practices-prevent-thresholds-innovation-summit-2025__17/tree/main/documentation); summarize key takeaways here so the public story stays current.

---

## Cite & reuse
If you use these materials, please cite:

> Oldfather, M., Stiefel, M., Molitor, C., Reed, S., Miller, B., Tangen, S., Dudney, J. (2025). *[Title of Work] — Innovation Summit 2025 (Group [Number]).* [URL if available]

License: CC-BY-4.0 unless noted. See dataset licenses on the **[Data](data.md)** page.

---

<!-- EDIT HINTS
- Upload images to docs/assets/ and reference as assets/filename.png
- Keep images ~1200 px wide; avoid >5–8 MB per file.
- Use short, active sentences; this is a scrolling “slide deck.”
- Update this page at least once per day during the sprint.
-->
