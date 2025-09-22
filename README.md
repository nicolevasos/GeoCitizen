# GeoCitizen – Digital Tools for EUDR Compliance and Risk Benchmarking

## Overview
This repository contains the outputs from the internship **“Digital Tools for EUDR Compliance and Risk Benchmarking”** conducted at GeoCitizen from **July 15th to September 9th, 2025**.  

The project focuses on:  

- Empowering **smallholder farmers** with a **SELF-EUDR tool** (based on GeoCitizen) to perform geolocation-based deforestation risk self-assessments.  
- **Benchmarking deforestation risk analysis platforms** such as WHISP and FarmVibes.AI to evaluate their transparency, usability, and consistency.  

The repository includes Jupyter notebooks, API tests, prototype implementations, and a benchmarking framework for risk analysis platforms.  

---

## Objectives
1. Develop a **SELF-EUDR risk self-check tool** for smallholder farmers using WHISP and Earth Observation (EO) insights.  
2. Integrate additional EO data (vegetation health, land cover change) to enhance risk analysis for actionable insights.  
3. Design a **benchmarking framework** to compare multiple risk analysis platforms based on accuracy, usability, transparency, and consistency.  

---

## Repository Structure
```
├── notebooks           # Jupyter notebooks for workflow testing and prototype development
│ ├── WHISP             # What Is in That Plot
│ ├── SAM2GEO           # Segment Anything Model for Geospatial Modelling
│ └── S2DR3             # Sentinel-2 Deep Resolution 3.0 imagery enhancement
├── data/               # Sample polygon datasets for testing
├── docs/               # Documentation, references, and reports
└── README.md           # Project overview (this file)
```

---

## Setup & Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/nicolevasos/GeoCitizen.git
   cd GeoCitizen
   ```
2. **Create a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Mac/Linux
   venv\Scripts\activate      # On Windows   
   ```
3. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

   ## Usage

- Run Jupyter notebooks in `notebooks/` to explore workflows and prototype development.  
- Use scripts in `apis/` to connect with WHISP or other geospatial models.  
- Test the **SELF-EUDR prototype** with sample AOI (Area of Interest) datasets.  

---

## Key Work Packages & Progress

### WP1: Onboarding and Research
- Studied EUDR requirements for smallholders.  
- Explored relevant tools: WHISP, SAM2GEO, S2DR3, FarmVibes.AI, and Color33.  
- Investigated input/output formats and data schemas for integration.  

### WP2: SELF-EUDR Tool Prototype
- Tested WHISP via QGIS plugin, App, Earthmap, and Python package.  
- Applied SAM2GEO to enhance polygon geometries.  
- Used S2DR3 for offline-ready satellite image enhancements.  
- Produced a functional prototype demonstrating farmer-friendly risk self-assessment.  

### WP3: Risk Platform Benchmarking
- Conducted automated queries on representative polygons.  
- Compared platforms using criteria: **accuracy, usability, transparency, consistency**.  
- Delivered a GitHub repository with notebooks, a customized WHISP dashboard, and documentation for reproducible benchmarking.  

---

## Results & Contributions
- **SELF-EUDR prototype**: Farmers can submit geolocation data and receive deforestation risk assessments.  
- **Benchmarking framework**: Evaluates multiple risk analysis platforms for smallholder suitability.  
- **Documentation & reproducible workflows**: GitHub repository and WHISP dashboard serve as standalone resources for further development and adoption.  
- Explored EO enhancements (vegetation health, land cover change) to provide actionable insights.  

---

## Challenges & Learnings
- Limited or inconsistent API documentation required additional troubleshooting.  
- Standardizing polygon datasets across platforms was essential for meaningful benchmarking.  
- Translating complex outputs into actionable insights highlighted the importance of user-centered design.  
- Developed reproducible workflows and comprehensive documentation to ensure transparency and accessibility.  

---

## Future Work
- Integrate EO enhancements into the SELF-EUDR tool for **real-time risk self-assessment**.  
- Expand benchmarking to additional platforms and datasets for improved accuracy.  
- Conduct **user-centered testing** with smallholder farmers to refine usability.  
- Maintain and iterate on the GitHub repository and WHISP dashboard to ensure reproducibility and broader adoption.  

---

## Resources & References
- [GeoCitizen GitHub Repo](https://github.com/nicolevasos/GeoCitizen)  
- [WHISP Dashboard – GeoCitizen version](https://github.com/nicolevasos/WHISP-Dashboard)  
- [WHISP](https://github.com/forestdatapartnership/whisp)  
- [FarmVibes.AI](https://github.com/microsoft/farmvibes-ai)  
- [OpenForis](https://openforis.org/)  
- [WHISP Dashboards](https://github.com/forestdatapartnership/whisp-dashboards)  
