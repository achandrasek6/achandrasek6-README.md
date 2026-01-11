# Aravind Chandrasekaran
## Bioinformatics Engineer | Genomics/NGS + MLOps | Nextflow · AWS · Docker · Terraform · CI/CD

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/aravind-chandrasekaran-254793118)
[![GitHub followers](https://img.shields.io/github/followers/achandrasek6?label=Follow&style=social)](https://github.com/achandrasek6)

I build cloud-native genomics systems and reproducible pipelines, with a focus on production-grade orchestration, explainable ML, and clear evidence artifacts.

**Interested in:** Bioinformatics Engineer, Genomics ML Engineer, MLOps (omics-facing)

---

## ⭐ Featured Projects

### 1) SARS-CoV-2 CFR Prediction Platform (Genomes → Risk Scores)
**Repo:** https://github.com/achandrasek6/Covid-Mortality-Prediction  
**Live demo:** https://www.covid-cfr-predictor.com (API key on request)


A two-service genomics platform:
- **Async web UI (React/Vite)** for FASTA/multi-FASTA batch scoring + artifact downloads
- **Low-latency FastAPI “calculator”** for mutation JSON “what-if” scoring with per-mutation delta contributions

**Stack highlights:** Nextflow DSL2 on AWS Batch, Docker images in ECR, Terraform-managed infra, AWS control plane (API Gateway/Lambda, DynamoDB, EventBridge, S3 presigned outputs), CI/CD via GitHub Actions (OIDC → Buildx → ECR).  

**Modeling:** interpretable Lasso baseline with robustness controls + SHAP/LIME; DNABERT deep-learning GPU baseline (lower RMSE; integration underway).

---

### 2) Microbial WGS Assembly & QC (ISO1–ISO3, Wastewater Isolates)
**Repo:** https://github.com/achandrasek6/Microbial-Genome-Assembly-QC

End-to-end microbial assembly + QC workflow for three wastewater isolates (ISO1–ISO3), with preserved evidence artifacts (reports/logs) for reproducible review:
- **FastQC/MultiQC → Trimmomatic → SPAdes → QUAST → BUSCO** (Flavobacteriia lineage set)
- Contiguity (**Nx/N50/L50**), GC distribution, completeness summaries, and outlier interpretation

---

### 3) Breast Cancer Tumor Detection (scRNA-seq → ML Classifier)
**Repo:** https://github.com/achandrasek6/Breast-Cancer-Predictor

Breast cancer tumor detection from breast tissue scRNA-seq gene expression using an R/Python hybrid pipeline: preprocessing in **R (tidyverse)** and modeling in **Python (scikit-learn)** with a **Random Forest** classifier evaluated via **LOOCV**.

---

## 🧰 Additional Toolkits
- **ESR1-Motif-Scanner** — PWM log-odds motif scanning CLI (15-mers, both strands)  
  https://github.com/achandrasek6/ESR1-Motif-Scanner
- **Enzyme-Variant-Profiler** — multiple sequence alignments + residue usage profiling across species  
  https://github.com/achandrasek6/Enzyme-Variant-Profiler
- **Protein-Reciprocal-Hits** — best reciprocal hits for putative orthology (BLOSUM62)  
  https://github.com/achandrasek6/Protein-Reciprocal-Hits

---

## 🧠 Skills (high level)
**Languages:** Python, R, Bash  
**Genomics/NGS:** FASTA/FASTQ, SAM/BAM/CRAM, VCF/BCF; MAFFT; BLAST; SAMtools/BCFtools; BEDTools; tabix/bgzip  
**Transcriptomics:** RNA-seq (STAR, DESeq2; Galaxy workflows), scRNA-seq  
**Microbial assembly/QC:** FastQC/MultiQC; Trimmomatic; SPAdes; QUAST; BUSCO  
**ML/MLOps:** scikit-learn, TensorFlow, Hugging Face; SHAP/LIME; CV + metrics  
**Platform:** Nextflow DSL2; Docker; Terraform; AWS (Batch, ECS/Fargate, API Gateway, Lambda, S3, DynamoDB, EventBridge, CloudWatch, ECR); GitHub Actions CI/CD (OIDC/Buildx)

---

## 📚 Publications
- *Genome-Driven Prediction of SARS-CoV-2 Case-Fatality Rate* — Wisconsin Online Collaboratives (Aug 2025)

---

## 📫 Contact
- LinkedIn: https://www.linkedin.com/in/aravind-chandrasekaran-254793118
- Email: aravind_plano@yahoo.com
