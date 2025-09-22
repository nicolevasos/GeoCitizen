# GeoCitizen -Digital Tools for EUDR Compliance and Risk Benchmarking

## Overview
This repository hosts the work from the internship **Digital Tools for EUDR Compliance and Risk Benchmarking**.  
The project focuses on:  

- Empowering **smallholder farmers** with a farmer-friendly **SELF-EUDR tool** (based on GeoCitizen).  
- **Benchmarking risk analysis platforms** such as WHISP and FarmVibes.AI to evaluate their transparency, usability, and consistency.  

The repo contains Jupyter notebooks, API tests, and prototype implementations for risk analysis and benchmarking.  

---

## Objectives
1. Prototype a **SELF-EUDR risk self-check tool** using WHISP and Earth Observation insights.  
2. Develop a **benchmarking framework** to compare risk analysis platforms for geolocation checks.  

---

## Repository Structure

```
├── notebooks & apis/ # Jupyter notebooks for testing APIs and workflows
├────── WHISP
├────── SAM2
├────── Raster imagery enhacement
├────── Risk Assesment Dashboard - Based on WHISP sample data
├── benchmarking/ # Scripts for comparing risk platforms
├── data/ # Sample polygon datasets for testing
├── docs/ # Documentation, references, and reports
└── README.md # Project overview (this file)
```
---

## Setup & Installation
1. **Clone the repository**  
   ```bash
   git clone https://github.com/nicolevasos/GeoCitizen.git
   cd GeoCitizen
2. Create a virtual environment
  ```python -m venv venv
    source venv/bin/activate   # On Mac/Linux
    venv\Scripts\activate      # On Windows
   ```
3. Install dependencies
   ```
   pip install -r requirements.txt
   ```
---

## Usage

- Run Jupyter notebooks in notebooks/ to test APIs and workflows.
- Use scripts in apis/ to connect with WHISP and FarmVibes.AI.
- Explore the SELF-EUDR prototype in prototype/.
- Run benchmarking experiments from benchmarking/.

---
## Expected Outcomes

- SELF-EUDR prototype tool (risk self-check for farmers).
- Benchmarking framework for evaluating multiple risk analysis platforms.
- A documented workflow for integrating Earth Observation insights into compliance tools.

---
## Resources

- WHISP
- FarmVibes.AI
- GeoCitizen
- WHISP Dashboards
