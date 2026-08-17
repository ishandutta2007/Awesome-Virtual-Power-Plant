# Awesome-Virtual-Power-Plant

## Top Virtual Power Plant (VPP) Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on DER Aggregation, Flexibility Markets, Demand Response, Battery & EV Orchestration, Grid Services & Real-Time Dispatch*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Virtual Power Plants (VPPs)**. These systems aggregate distributed energy resources (DERs) — solar, batteries, EVs, flexible loads, and thermostats — into coordinated portfolios that provide grid services, trade in energy markets, and optimize behind-the-meter assets.

**Examples** include AutoGrid, Next Kraftwerke, Tesla Autobidder, Sunverge, GridBeyond, Enel X, Piclo, EnergyHub, Limejump, and Flexitricity (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for VPP simulation, DERMS, flexibility optimization, DER modeling, and open energy management stacks — ideal for utilities, aggregators, researchers, and developers seeking transparent, standards-based control of distributed resources.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[AutoGrid (Schneider Electric)](https://www.autogrid.com/)**  
  Hardware-agnostic VPP and flexibility platform that orchestrates multi-OEM batteries, EV chargers, HVAC, and other DERs for grid services and demand response.

- **[Next Kraftwerke](https://www.next-kraftwerke.com/)**  
  One of Europe’s largest independent VPPs, aggregating thousands of flexible assets and trading them across power markets and balancing services.

- **[Tesla Autobidder](https://www.tesla.com/)**  
  Closed-ecosystem real-time trading and optimization platform that bids Tesla Powerwall, Megapack, and related assets into energy and ancillary service markets.

- **[Sunverge](https://www.sunverge.com/)**  
  Distributed energy resource management and VPP software focused on residential and commercial solar-plus-storage orchestration.

- **[GridBeyond](https://www.gridbeyond.com/)**  
  AI-driven flexibility platform that aggregates industrial, commercial, and other flexible loads for market participation and grid support.

- **[Enel X](https://www.enelx.com/)**  
  Global demand-response and VPP solutions that monetize flexible capacity from commercial, industrial, and residential assets.

- **[Piclo](https://www.piclo.energy/)**  
  Marketplace platform connecting flexibility providers with grid operators and buyers of flexibility services.

- **[EnergyHub](https://www.energyhub.com/)**  
  Leading residential DER aggregation platform that turns thermostats, batteries, EV chargers, and other devices into utility-scale VPPs.

- **[Limejump](https://www.limejump.com/)**  
  UK-focused VPP and flexibility platform (part of Shell) that optimizes and trades distributed generation and flexible demand.

- **[Flexitricity](https://www.flexitricity.com/)**  
  Demand-side response and VPP operator that aggregates industrial and commercial flexibility for balancing and capacity markets.

## Open-Source GitHub Projects
- **[Virtual Power Plant Platform (vinerya)](https://github.com/vinerya/virtual-power-plant)**  
  Comprehensive open-source VPP platform with production-ready optimization, multi-protocol DER control, V2G support, and benchmarking tools.

- **[FlexMeasures (LF Energy)](https://flexmeasures.io/)**  
  Open-source energy management and flexibility toolkit for optimizing schedules of batteries, EVs, processes, and other flexible assets; designed for EMS and VPP use cases.

- **[NREL Virtual Battery Aggregator](https://github.com/NREL/virtual-battery-aggregator)**  
  Open-source algorithms that aggregate DERs into a virtual battery model and dispatch setpoints for DERMS platforms.

- **[OpenDER (EPRI)](https://github.com/epri-dev/OpenDER)**  
  Open-source DER model implementing IEEE 1547-2018 behaviors for steady-state and dynamic studies of inverter-based resources.

- **[DERIM Middleware](https://github.com/iceccarelli/derim-middleware)**  
  Open-source smart-grid digital-twin middleware for integrating, monitoring, controlling, and simulating heterogeneous DERs.

- **[EnergyLink Open-Source DERMS](https://github.com/vpdeva/Energylink-Open-Source-DERMS)**  
  Open-source energy data exchange and Distributed Energy Resource Management System with connectors, analytics, and dashboards.

- **[vpp-sim](https://github.com/jdhoffa/vpp-sim)**  
  Lightweight open-source simulator for small commercial & industrial VPPs, modeling solar, batteries, flexible loads, and demand-response events.

- **[Alliander DER Scheduling](https://github.com/alliander-opensource/der-scheduling)**  
  Open-source scheduling stack for DER control according to IEC 61850 standards.

- **[GridAPPS-D and related DERMS test environments](https://github.com/)**  
  Open-source platforms and modeling environments for developing and testing DERMS applications on distribution systems.

- **[Custom flexibility optimizers & Gym environments](https://github.com/)**  
  Research codebases for demand-response, local electricity markets, and reinforcement-learning based flexibility control.

### Additional Strong Open-Source Options
- OpenEMS, Home Assistant energy integrations, and other open EMS platforms that can feed into VPP logic.
- IEC 61850, IEEE 2030.5, OpenADR, and SunSpec protocol stacks and clients.
- Time-series databases (InfluxDB, Timescale) + Grafana for DER monitoring and VPP dashboards.
- Optimization libraries (OR-Tools, Pyomo, CVXPY) applied to multi-period dispatch and market bidding.
- Co-simulation frameworks (GridLAB-D, OpenDSS, HELICS) for studying VPP impacts on the grid.

**Frameworks for building custom systems**: Use **FlexMeasures** or the **vinerya VPP platform** as the core optimization and scheduling layer, model individual DERs with **OpenDER** or battery abstractions, aggregate them via the **NREL Virtual Battery Aggregator** or custom ADMM/coordination logic, and connect to devices through open protocols (IEEE 2030.5, Modbus, OCPP, OpenADR). Simulate portfolios with **vpp-sim** or GridAPPS-D before live deployment. Store telemetry in open time-series stores and expose market/grid-service interfaces via APIs.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- VPPs interact with critical energy infrastructure and regulated markets. Open-source components are powerful for research, simulation, and non-critical control layers but must be thoroughly validated, cybersecurity-hardened, and approved by relevant grid operators or regulators before operational use.
- Always ensure compliance with local interconnection standards, market rules, data privacy, and grid codes.

---
**Made for utilities, aggregators, energy startups, and researchers building the flexible grid of the future.**
Let's make virtual power plants more open, interoperable, and democratically controllable.
