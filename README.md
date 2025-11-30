# Thai Real-Time GDP Nowcasting System  
_A Mixed-Frequency VAR Platform for Real GDP Monitoring_

This repository provides the public project structure for the research project  
“Thai Real-Time Nowcasting System: A Mixed-Frequency VAR Platform for Real GDP Monitoring.”

The goal is to build a transparent, reproducible, and modular system for real-time monitoring and nowcasting of Thailand’s quarterly real GDP using mixed-frequency macroeconomic indicators.

---

📌 Current Status (v0.1 — Repository Skeleton)

This version contains:

- Repository layout and directory hierarchy  
- Placeholder modules for:
  - data ingestion  
  - indicator filtering  
  - MF-VAR modelling  
- Documentation stubs and example scripts  
- Basic project metadata (README, license, repo structure)

⚠️ Note:  
The full implementation is intentionally withheld.  
The completed framework will be released after internal review and project evaluation.

---

🚀 Development Roadmap

This repository will evolve in several stages as the project progresses.  
The planned development timeline is as follows:

Phase 1 — Data Architecture and Metadata (Q1)
- Define unified data schema for monthly and quarterly indicators  
- Build metadata tables for BOT series  
- Implement safe, reproducible ingestion wrappers (Python)  
- Validate data consistency and frequency alignment  

Phase 2 — Indicator Screening and Selection (Q1–Q2)
- Compute coverage, completeness, and variance-based filters  
- Implement EM + Kalman pre-processing for ragged edges  
- Develop importance-score components  
- Test alternative relevance metrics (MI, LPS, ML relevance measures)  
- Produce ranked indicator lists  

Phase 3 — MF-VAR Estimation Framework (Q2–Q3)
- Specify mixed-frequency state-space structure  
- Implement Bayesian or classical estimation  
- Run rolling pseudo–real-time experiments  
- Tune hyperparameters and update routines  

Phase 4 — Nowcasting Engine and Evaluation (Q3)
- Generate point and density nowcasts  
- Benchmark against simple AR or bridge models  
- Evaluate real-time performance (RMSFE, LPS, coverage)  
- Produce monthly and quarterly update scripts  

Phase 5 — Documentation and Public Release (Q4)
- Release full reproducible pipeline  
- Add API usage guides and example notebooks  
- Publish documentation website (MkDocs or Sphinx)  
- Finalize replication package for publication  

---

📦 Final Deliverables
At completion, the repository will include:

- A fully reproducible end-to-end MF-VAR nowcasting pipeline  
- Automatic indicator-selection system  
- Prebuilt metadata tables for Thai macroeconomic indicators  
- Pseudo real-time forecasting framework  
- Documentation, examples, and user guides  

---

🤝 Contributions
The full code will be released after internal review and project evaluation.  
Issues and feature suggestions will be opened at that stage.

---

📞 Contact
Paponpat Taveeapiradeecharoen  
School of Economics, Mae Fah Luang University  
Email: paponpat.tav@mfu.ac.th


