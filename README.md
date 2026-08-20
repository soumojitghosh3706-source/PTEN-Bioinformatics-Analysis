# 🧬 Comprehensive Bioinformatics Analysis of the Human PTEN Gene and Protein

<p align="center">
  <img src="images/repository_banner.png" alt="PTEN Bioinformatics Analysis Banner" width="100%">
</p>

<p align="center">
An integrated <b>in silico</b> bioinformatics study investigating the genomic organization, protein structure, molecular interactions, functional enrichment, disease association, and clinical relevance of the human <b>PTEN</b> gene.
</p>

---

# 📖 Project Overview

The **Phosphatase and Tensin Homolog (PTEN)** gene is one of the most important tumor suppressor genes in humans. PTEN negatively regulates the PI3K/AKT signaling pathway and plays essential roles in cell proliferation, apoptosis, migration, metabolism, and genomic stability. Mutations or loss of PTEN function are associated with numerous cancers and inherited disorders.

This project presents a comprehensive computational analysis of the human PTEN gene and protein using multiple publicly available bioinformatics databases and computational tools. The study integrates genomic, proteomic, structural, functional, and clinical analyses into a single reproducible workflow.

---

# 🎯 Project Objectives

- Retrieve and annotate the human PTEN gene.
- Identify the canonical transcript and protein sequence.
- Perform coding sequence and ORF analysis.
- Analyze protein physicochemical properties.
- Identify conserved functional domains.
- Predict protein secondary and tertiary structures.
- Construct the protein–protein interaction network.
- Perform Gene Ontology and pathway enrichment analyses.
- Investigate disease-associated variants.
- Analyze PTEN expression and survival across cancers.

---

# 🔬 Bioinformatics Workflow

<p align="center">
<img src="images/workflow.png" width="950">
</p>

**Figure 1.** Bioinformatics workflow employed for the comprehensive analysis of the human PTEN gene and protein.

---

# 📊 Analysis Results

## 1. Gene Annotation

<p align="center">
<img src="images/gene_annotation.png" width="900">
</p>

Gene annotation was performed using the NCBI Gene database to determine chromosomal location, transcript information, genomic organization, and reference sequence identifiers.

---

## 2. Open Reading Frame (ORF) Analysis

<p align="center">
<img src="images/ORF_analysis.png" width="900">
</p>

The canonical coding sequence was analyzed using NCBI ORF Finder to verify the protein-coding region and translation frame.

---

## 3. Protein Structure Prediction

<p align="center">
<img src="images/protein_structure.png" width="650">
</p>

The three-dimensional structure of PTEN was obtained from the AlphaFold Protein Structure Database and examined together with secondary structural information.

---

## 4. Protein–Protein Interaction Network

<p align="center">
<img src="images/PPI_network.png" width="700">
</p>

STRING database analysis identified major PTEN interaction partners involved in PI3K/AKT signaling, apoptosis, cell adhesion, and tumor suppression.

---

## 5. Gene Ontology Enrichment

<p align="center">
<img src="images/GO_enrichment.png" width="900">
</p>

GO enrichment analysis identified biological processes, molecular functions, and cellular components significantly associated with PTEN.

---

## 6. Pathway Enrichment Analysis

<p align="center">
<img src="images/pathway_analysis.png" width="900">
</p>

Reactome pathway analysis demonstrated PTEN involvement in signal transduction, apoptosis, immune regulation, and cancer-associated pathways.

---

## 7. Gene Expression Analysis

<p align="center">
<img src="images/gene_expression.png" width="900">
</p>

GEPIA3 analysis compared PTEN expression between tumor and normal tissues across multiple cancer types.

---

## 8. Survival Analysis

<p align="center">
<img src="images/survival_analysis.png" width="750">
</p>

Kaplan–Meier survival analysis evaluated the prognostic significance of PTEN expression in human cancers.

---

## 9. Disease Association

<p align="center">
<img src="images/disease_association.png" width="900">
</p>

ClinVar and OMIM resources were used to investigate disease-associated PTEN variants and their clinical relevance.

---

# 📁 Repository Structure

```text
PTEN-Bioinformatics-Analysis/
│
├── README.md
├── LICENSE
├── RESULTS.md
│
├── data/
│   ├── PTEN_gene_information.txt
│   ├── PTEN_CDS.fasta
│   ├── PTEN_protein_sequence.fasta
│   ├── ProtParam_results.txt
│   ├── STRING_network_statistics.txt
│   ├── GO_enrichment_results.csv
│   ├── Reactome_pathways.csv
│   └── GEPIA_expression_summary.txt
│
├── docs/
│   └── project_summary.md
│
└── images/
    ├── repository_banner.png
    ├── workflow.png
    ├── gene_annotation.png
    ├── ORF_analysis.png
    ├── protein_structure.png
    ├── PPI_network.png
    ├── GO_enrichment.png
    ├── pathway_analysis.png
    ├── gene_expression.png
    ├── survival_analysis.png
    └── disease_association.png
```

---

# 🛠️ Bioinformatics Databases and Tools

| Database / Tool | Purpose |
|-----------------|---------|
| NCBI Gene | Gene annotation |
| Genome Data Viewer (GDV) | Genomic visualization |
| RefSeq | Canonical transcript and CDS |
| UniProt | Protein sequence retrieval |
| ORF Finder | Open Reading Frame analysis |
| ExPASy ProtParam | Physicochemical characterization |
| Conserved Domain Database (CDD) | Conserved domain identification |
| AlphaFold Protein Structure Database | Protein structure prediction |
| DSSP | Secondary structure analysis |
| STRING | Protein–protein interaction analysis |
| ShinyGO | GO enrichment analysis |
| Reactome | Pathway enrichment |
| OMIM | Disease information |
| ClinVar | Variant interpretation |
| Therapeutic Target Database (TTD) | Therapeutic relevance |
| GEPIA3 | Expression and survival analysis |

---

# 📂 Supporting Files

The repository also includes:

- PTEN nucleotide coding sequence (CDS)
- Canonical PTEN protein FASTA sequence
- ProtParam physicochemical analysis
- STRING interaction statistics
- GO enrichment results
- Reactome pathway summary
- GEPIA expression summary
- Comprehensive project summary

---
## References

See [References](Docs/References.md) for the databases, tools, and scientific literature used in this analysis.

---
# 📄 Project Summary

A detailed project summary is available in:

```text
docs/project_summary.md
```

---

# 🚀 Future Scope

Potential future extensions include:

- Comparative genomics
- Molecular docking
- Molecular dynamics simulation
- Evolutionary analysis
- RNA-seq integration
- Machine learning-based variant prediction

---

# 👨‍🔬 Author

**Soumojit Ghosh**

B.Sc. Biotechnology  
St. Xavier's College, Burdwan

GitHub Profile:
https://github.com/soumojitghosh3706-source

---

# 📜 License

This project is licensed under the **MIT License**.
