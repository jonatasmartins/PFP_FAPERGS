# PFP_FAPERGS – Energy Efficiency in SMEs (System Dynamics + RDM)

## Overview

This repository contains the computational and analytical components of the research project:

**"Gestão de Energia e Eficiência Energética em PMEs do Rio Grande do Sul: Estimativa do Impacto Econômico com uso de Modelagem Dinâmica de Sistemas e Estratégias de Robust Decision Making"**

Developed at:
- Instituto Federal do Rio Grande do Sul (IFRS)
- Campus Bento Gonçalves

Funded by:
- FAPERGS / SEFAZ-RS – Applied Research Program in Public Finance (PFP)

---

## Research Purpose

The project investigates how energy efficiency adoption affects:

- Operational costs
- Competitiveness
- Investment capacity
- Public policy outcomes

with a focus on **industrial SMEs in Southern Brazil**.

The central research question is:

> *Which policy design for energy efficiency is least vulnerable to uncertainty and capable of producing robust results across different future conditions?*

---

## Methodological Architecture

The project integrates three layers:

### 1. Scientific Evidence
- Systematic literature review (PRISMA protocol)
- Focus on energy efficiency, policy instruments, and SMEs

### 2. Empirical Evidence
- Real consumption data from ~350 industrial units
- Variables:
  - Energy consumption (kWh)
  - Demand (kW)
  - Reactive energy
  - Distributed generation

### 3. Dynamic Modeling
- System Dynamics simulation (Python-based)
- Captures:
  - Feedback loops
  - Investment-reinvestment cycles
  - Saturation effects
  - Nonlinear behavior

---

## Key Concepts

- Energy efficiency as an **operational capability**
- Reinforcement loops (cost savings → reinvestment)
- Saturation (diminishing returns)
- Policy robustness vs optimality
- Uncertainty-aware decision-making (RDM)

---

## Repository Structure

```bash
.
├── data/                # Raw and processed datasets
├── docs/                # Documentation and reports
├── examples/            # Example scenarios and simulations
├── notebooks/           # Exploratory and analytical notebooks
├── src/sd_simulation/   # Core System Dynamics engine
├── README.md
├── LICENSE
├── requirements.txt
└── pyproject.toml
