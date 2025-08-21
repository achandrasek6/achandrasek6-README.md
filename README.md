# ML engineer | bioinformatics & genetics

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/aravind-chandrasekaran-254793118)
[![GitHub followers](https://img.shields.io/github/followers/achandrasek6?label=Follow&style=social)](https://github.com/achandrasek6)
[![covid-mortality-prediction](https://img.shields.io/github/stars/achandrasek6/covid-mortality-prediction?label=covid-mortality-prediction&style=social)](https://github.com/achandrasek6/covid-mortality-prediction)
[![Breast-Cancer-Predictor](https://img.shields.io/github/stars/achandrasek6/Breast-Cancer-Predictor?label=Breast-Cancer-Predictor&style=social)](https://github.com/achandrasek6/Breast-Cancer-Predictor)
[![ESR1-Motif-Scanner](https://img.shields.io/github/stars/achandrasek6/ESR1-Motif-Scanner?label=ESR1-Motif-Scanner&style=social)](https://github.com/achandrasek6/ESR1-Motif-Scanner)

I build reproducible genomics pipelines and explainable models (Nextflow, Docker, AWS; Python/R).

## Featured Projects
- **covid-mortality-prediction** — End-to-end SARS-CoV-2 pipeline: MAFFT → binary mutation features → Lasso (scikit-learn) + DNABERT; SHAP/LIME + robustness (label permutations, feature shuffles, ablations). Batch scoring via CLI/Nextflow.  
  _R² = 0.84 on held-out; ~5k → ~60 features via L1 sparsity._  
  🔗 https://github.com/achandrasek6/covid-mortality-prediction

- **Breast-Cancer-Predictor** — R-based preprocessing of single-cell breast tissue RNA-seq + Python Random Forest with leave-one-out CV to detect tumor presence.  
  _Accuracy 0.889; ROC AUC 0.775._  
  🔗 https://github.com/achandrasek6/Breast-Cancer-Predictor

- **ESR1-Motif-Scanner** — Python CLI that scans DNA for ESR1-binding motifs using PWM log-odds across 15-mer windows on both strands; CSV/bed-like outputs with thresholds.  
  🔗 https://github.com/achandrasek6/ESR1-Motif-Scanner

## Other Toolkits
- **Local-Global-Alignment-Tools** (R) — Smith–Waterman (local) & Needleman–Wunsch (global) with edit-graph visualization.  
  🔗 https://github.com/achandrasek6/Local-Global-Alignment-Tools
- **Protein-Reciprocal-Hits** (Python) — BLOSUM62 pairwise alignment to find best reciprocal hits (human ↔ chicken) for putative orthologs.  
  🔗 https://github.com/achandrasek6/Protein-Reciprocal-Hits
- **Phylogenetic-Tree-Toolkit** (Python) — Build/query/visualize trees via UPGMA; quick plotting with Turtle graphics.  
  🔗 https://github.com/achandrasek6/Phylogenetic-Tree-Toolkit

## Now / In Progress
- CI/CD (GitHub Actions → Docker/ECR), MLflow/DVC versioning  
- AWS Batch/ECS Fargate API (FastAPI + API Gateway), S3 pre-signed I/O, SQS  
- Drift reports & monitoring for genomics models

## Skills
Python, R, scikit-learn, TensorFlow/Transformers, Biopython, tidyverse • Nextflow (DSL2), Docker, AWS Batch • MAFFT, SAMtools/BCFtools, VCFtools, BEDTools • SHAP/LIME, CV/metrics • NCBI/Ensembl/UCSC

## Publications
- _Genome-Driven Prediction of SARS-CoV-2 Case-Fatality Rate_, Wisconsin Online Collaboratives (In Press, Aug 2025)

## Contact
[LinkedIn](https://www.linkedin.com/in/aravind-chandrasekaran-254793118) • aravind_plano@yahoo.com
