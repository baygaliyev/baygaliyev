# Gurban Aliyev

I work on **who gets exposed to what and where** — using GPS trajectory data,
network science and agent-based simulation.

📍 Pisa, Italy · ✉️ [qrb.aliyev@gmail.com](mailto:qrb.aliyev@gmail.com)

## Current

- **Visiting Researcher**, MRC Epidemiology Unit, University of Cambridge
  (Nov 2025 – Dec 2026) — route choice under flood and heat scenarios using MATSim
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

The honest version: most of my headline results come from **constrained-route
scenarios on synthetic city models**, not measured populations, and the
behavioural side assumes rational route choice without calibration. Each repo
documents its own limitations rather than only the wins.

## Selected work

| Paper | Venue |
|---|---|
| *Vehicle-Pedestrian Optimization Framework for Exposure-Aware Routing* | Mobile Networks and Applications, 2025 (journal) |
| *Optimization of Exposure-Aware Routing for Vehicles and Pedestrians* | SSTD, 2025 |
| *Exploiting Vehicular Data for Exposure-Aware Pedestrian Routing* | IEEE MDM, 2025 |
| *From GPS Traces to Individual Emission Exposure: A Data-Driven Four-Step Process* | EAI INTSYS, 2024 |
| *Analysis, Prediction and Mitigation of Exposure to Vehicular Air Pollution* | SEBD, 2023 |
| *Optimizing Exposure-Aware Routing for Vehicles and Pedestrians* | CCS, 2025 (poster) |

## Repos

| Repo | What it is |
|---|---|
| [exawaro](https://github.com/baygaliyev/exawaro) | Exposure-aware routing and behaviour simulation for pedestrians and vehicles on OpenStreetMap networks. Python (`osmnx`, `networkx`, `shapely`). Code from my thesis. |
| [eide](https://github.com/baygaliyev/eide) | Code for the four-step GPS-trace → emission-exposure process (INTSYS 2024). |
| [matsim-project-gurban](https://github.com/baygaliyev/matsim-project-gurban) | *Fork of upstream MATSim* — my own experiment scripts for flood/heat route choice. |

Also here: MSc coursework notebooks (data mining, social network analysis, big
data analytics) and a few forks.

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
