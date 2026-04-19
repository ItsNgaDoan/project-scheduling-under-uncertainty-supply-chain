# Project Scheduling Under Uncertainty (SkyTrack)


## Overview

This project evaluates whether a drone product launch can meet a **90-day deadline** under uncertain task durations.

Set in a **supply chain context**, the analysis involves supplier coordination, inventory planning, and distribution strategy for launching the SkyTrack drone.

Using probabilistic modelling and scenario analysis, the project assesses feasibility and identifies the most effective execution strategy.


## Problem Context

The baseline plan showed an expected duration of **103 days**, exceeding the target.

More importantly, the probability of completing within 90 days was **less than 1%**, making the original plan highly unrealistic.

A dual critical path structure further increased execution risk, requiring close monitoring of multiple task sequences.


## Approach

- Applied **PERT** to model uncertainty in task durations  
- Identified **critical paths** and key risk drivers  
- Calculated probability of meeting the 90-day deadline  
- Performed **cost–time trade-off (crashing) analysis**  
- Evaluated multiple execution scenarios  


## Key Results

- Baseline: **103 days**, <1% chance of meeting deadline  
- **91 days** → lowest total cost (~$131K), balanced option  
- **81 days** → ~95% probability of meeting deadline (aggressive)  
- **79 days** → fastest possible, but highest cost (~$138K)  


## Insight

The project highlights that scheduling decisions are not just about time.

The main challenge lies in balancing:
- **time (deadline pressure)**
- **cost (crashing impact)**
- **risk (uncertainty and dependencies)**

The presence of multiple critical paths makes the schedule highly sensitive to disruptions.


## Scenario Insights

- **Supplier delay** extended the project to 112 days and significantly reduced feasibility  
- **Reducing a key task duration** improved both cost and schedule efficiency  
- Even with full crashing, some risks cannot be fully eliminated  


## My Contribution

This project was completed as part of a team-based case study. I contributed to:

- analysing project dependencies and critical paths  
- modelling uncertainty using PERT  
- evaluating cost–time trade-offs across scenarios   


## What This Project Shows

- Scheduling under uncertainty  
- Probability-based decision-making  
- Critical path and risk analysis  
- Trade-off thinking (time vs cost vs risk)  


## Files

- [Case Brief](./skytrack-case-brief.pdf) — project scenario  
- [Analysis Report](./skytrack-analysis-report.pdf) — full analysis and results  
- [Requirements](./skytrack-analysis-requirements.pdf) — problem definition  
