# Gurban Aliyev

I work on **who gets exposed to what and where** — using GPS trajectory data, network science and agent-based simulation.

## Current

- **Postdoctoral Researcher**, University of Augsburg — Chair of Model-based
  Environmental Exposure Sciences (MBEES), EU Horizon Europe **PUREPOLIS**
  (Oct 2026 – Oct 2027). Agent-based (MATSim) population mobility for the Nantes
  and Valencia living labs, feeding exposure and health-impact assessment.
- **Visiting Researcher (remote)**, MRC Epidemiology Unit, Institute of Medical Sciences
  (IMS), University of Cambridge (Nov 2025 – Dec 2026) — route choice under flood
  and heat scenarios using MATSim
- **PhD in AI for Society**, University of Pisa — defended **28 August 2026 with
  distinction**. Thesis: *Analysis and Routing-Based Mitigation of Vehicular Air
  Pollution Exposure*

## Research

Vehicles choose the fastest route; pedestrians breathe whatever that route emits.
My work estimates vehicular emissions from GPS traces, maps who is exposed near
those roads, and asks whether routing can be optimised for health rather than
only for speed.

- **Emission estimation from GPS trajectories** — a data-driven four-step
  process, validated against urban air quality measurements
- **Spatial imputation** — extending emission estimates to areas with no
  trajectory coverage
- **Exposure-aware routing** — joint optimisation of pedestrian and vehicle paths
  against a time/exposure trade-off, selecting among alternatives by
  hypervolume contribution
- **MATSim route choice** under flood and heat scenarios (Greater Manchester,
  synthetic data)
- **Population mobility modelling** — agent-based (MATSim) simulation of
  full-population daily activities for population exposure and health-impact
  assessment (PUREPOLIS, Nantes & Valencia living labs)

The honest version: most of my headline results come from **constrained-route
scenarios on synthetic city models**, not measured populations, and the
behavioural side assumes rational route choice without calibration. Each repo
documents its own limitations rather than only the wins.

## Selected work

| Paper | Venue |
|---|---|
| *Vehicle-Pedestrian Optimization Framework for Exposure-Aware Routing* | [Mobile Networks and Applications 30(1):325–340, 2025](https://doi.org/10.1007/s11036-025-02459-4) (journal) |
| *Optimization of Exposure-Aware Routing for Vehicles and Pedestrians* | [ACM SSTD '25, pp. 119–122](https://doi.org/10.1145/3748777.3748808) — also presented as a **poster at CCS 2025** (Conference on Complex Systems, Siena); poster only, no talk |
| *Exploiting Vehicular Data for Exposure-Aware Pedestrian Routing* | [IEEE MDM 2025, pp. 11–19](https://doi.org/10.1109/MDM65600.2025.00022) |
| *From GPS Traces to Individual Emission Exposure: A Data-Driven Four-Step Process* | [EAI INTSYS 2024, LNCS 578:64–82](https://doi.org/10.1007/978-3-031-86370-7_5) |
| *Analysis, Prediction and Mitigation of Exposure to Vehicular Air Pollution* | [SEBD 2023, CEUR WS 3478:674–680](https://ceur-ws.org/Vol-3478/paper13.pdf) |

Full list: <https://kdd.isti.cnr.it/publications/filter> (matches ORCID, DBLP, Semantic Scholar).
PhD thesis (open access, CC BY): *Analysis and Routing-Based Mitigation of Vehicular
Air Pollution Exposure*, Università di Pisa / CNR — URN `etd-08142026-182359`.

## Repos

| Repo | What it is |
|---|---|
| [exawaro](https://github.com/baygaliyev/exawaro) | Exposure-aware routing and behaviour simulation for pedestrians and vehicles on OpenStreetMap networks. Python (`osmnx`, `networkx`, `shapely`). Code from my thesis. MIT licence. |
| [eide](https://github.com/baygaliyev/eide) | Code for the four-step GPS-trace → emission-exposure process (INTSYS 2024). MIT licence. |
| [matsim-manchester-flood-heat-routing](https://github.com/baygaliyev/matsim-manchester-flood-heat-routing) | *Fork of upstream MATSim* — my own experiment scripts for flood/heat route choice. |

## Coursework (MSc, University of Pisa)

| Repo | What it is |
|---|---|
| [unipi_data_mining_1](https://github.com/baygaliyev/unipi_data_mining_1) | Telco customer churn — K-Means, DBSCAN and hierarchical clustering, compared by silhouette. |
| [data_mining_2](https://github.com/baygaliyev/data_mining_2) | Air-quality time series — clustering, sequential patterns, k-NN / decision-tree classification, outlier detection. |
| [social_network_analysis](https://github.com/baygaliyev/social_network_analysis) | Stack Overflow hashtag graph — topology, community detection, link prediction. |
| [big_data_analytics](https://github.com/baygaliyev/big_data_analytics) | Car-crash prediction from individual mobility networks (London, Rome, Tuscany). |

## Coursework (PhD, University of Pisa)

| Repo | What it is |
|---|---|
| [deep_learning_lung_nodule_segmentization](https://github.com/baygaliyev/deep_learning_lung_nodule_segmentization) | Res U-Net vs. Attention U-Net vs. Attention Res U-Net for lung-nodule segmentation on LUNA16 CT scans (TensorFlow/Keras). |
| [xai_breast_tumor_explainability](https://github.com/baygaliyev/xai_breast_tumor_explainability) | Explaining a breast-tumour classifier with LIME, LORE and SHAP, against interpretable logistic-regression and decision-tree models. |

Also here: [SARN](https://github.com/baygaliyev/SARN) (fork of the EDBT 2023
road-network-embedding code) and [RFNEmission](https://github.com/baygaliyev/RFNEmission)
(GCN road-emission prediction, extended with train/eval scripts).

## Tooling

**Languages** — Python (primary), R, C, Java, LaTeX; SQL (PostgreSQL, MySQL, MS SQL Server); Stata
**Modelling & simulation** — agent-based simulation, routing optimisation, emissions estimation, network analysis, GIS/OSM, MATSim
**Data** — spatiotemporal analysis, spatial imputation, trajectory preprocessing, ETL

**Human languages** — English, Azerbaijani (native), Russian, Turkish, Italian (intermediate), German (elementary)

## Background

MSc Data Science and Business Informatics, University of Pisa — 110/110 *e lode*.
Erasmus semester, Vrije Universiteit Amsterdam (Computer Science, 2020–21).
BSc Business Administration, ADA University, Baku — *magna cum laude*.

Grants: ISTI-CNR **Grant for Young Mobility** (2025, funded the Cambridge visit),
PhD research grant in AI for Society (2022–25), merit-based admission grant (2018).
