# In Silico Screening of Phytochemicals Targeting Integrin-αv for Pulmonary Fibrosis

**Authors:** Muneeb Shahzad, Amna Fatima, Baitullah Haseeb, Muhammad Rehan  
**Institution:** Department of Biotechnology, University of Central Punjab, Lahore, Pakistan  
**Supervisor:** Dr. Hira Mubeen

---

## Overview

Idiopathic Pulmonary Fibrosis (IPF) is a progressive respiratory disease where healthy lung tissue transforms into stiff scar tissue. In Pakistan, the incidence is worsened by environmental pollutants — specifically smog (PM2.5) and cotton dust from the textile industry.

At the molecular level, these pollutants trigger overexpression of **Integrin Alpha-V (ITGAV)**, which acts as a molecular switch activating the TGF-β signaling pathway and driving uncontrolled lung scarring.

This study used **in silico (computational) methods** to screen natural phytochemicals as potential inhibitors of ITGAV — offering a cost-effective, non-toxic therapeutic strategy for high-risk populations including textile workers.

---

## Objectives

- Validate Integrin αv (ITGAV) as the disease target using gene expression data
- Screen natural phytochemicals as potential inhibitors via molecular docking
- Verify binding stability through molecular dynamics simulation and ADME analysis

---

## Methodology

The study followed a structured computational drug discovery pipeline:

```
Target Identification (NCBI GEO)
        ↓
Protein Structure Retrieval (PDB)
        ↓
Phytochemical Selection (PubChem)
        ↓
Active Site Prediction (PrankWeb)
        ↓
Molecular Docking (CB-DOCK2)
        ↓
Interaction Analysis (Discovery Studio)
        ↓
ADME & Toxicity Prediction (SwissADME)
        ↓
Molecular Dynamics Simulation (iMODS)
```

---

## Tools & Software Used

| Tool | Purpose |
|------|---------|
| NCBI GEO | Gene expression validation of ITGAV overexpression |
| RCSB PDB | Protein structure retrieval |
| PubChem | Phytochemical compound retrieval |
| PrankWeb | Active site prediction |
| CB-DOCK2 | Molecular docking |
| Discovery Studio | Interaction analysis (hydrogen & hydrophobic bonds) |
| SwissADME | ADME profiling and toxicity prediction (Boiled Egg Plot) |
| iMODS | Molecular dynamics simulation and normal mode analysis |
| Ramachandran Plot | Protein structure validation |

---

## Key Results

- **Target Validated:** NCBI GEO gene expression data confirmed ITGAV overexpression in fibrotic lung tissue
- **Best Ligand:** Curcumin identified as the most potent phytochemical inhibitor
- **Binding Score:** Exceeding **-7.0 kcal/mol**, indicating strong and stable binding affinity
- **Interactions:** Curcumin formed hydrogen and hydrophobic bonds within the ITGAV active site
- **Drug-likeness:** SwissADME analysis confirmed favourable ADME properties and low toxicity profile
- **Stability:** MD simulation confirmed stability of the Curcumin-ITGAV docked complex over time

---

## Conclusion

Curcumin was identified as a potent natural inhibitor of Integrin αv, effectively blocking the molecular switch that drives pulmonary fibrosis. This offers a promising, accessible therapeutic avenue — particularly relevant for Pakistan's textile workforce and urban populations exposed to smog and industrial pollutants.

---

## Relevance

This project addresses a real public health problem in Pakistan using modern computational drug discovery techniques. It demonstrates the application of bioinformatics, structural biology, and cheminformatics in identifying drug candidates without wet lab experimentation.

---

## References

- Chan, M. K.-K., et al. (2023)
- Farh, M. E.-A., et al. (2025)
- Hasan, M., et al. (2022)
- ITGAV Protein — NCBI Protein Database
- Curcumin — PubChem CID: 969516

---

## Contact

**Muneeb Shahzad**  
BS Biotechnology, University of Central Punjab  
LinkedIn: [Add your LinkedIn URL]  
GitHub: [Add your GitHub URL]
