Comprehensive Bioinformatics Analysis of the Human PTEN Gene and Protein
Project Summary
Abstract
The Phosphatase and Tensin Homolog (PTEN) gene is one of the most extensively studied tumour suppressor genes because of its fundamental role in regulating cell proliferation, apoptosis, metabolism, and genomic stability. Loss of PTEN function contributes to the development of numerous malignancies through dysregulation of the PI3K/AKT signalling pathway. This project presents a comprehensive in silico bioinformatics analysis of the human PTEN gene and its encoded protein using publicly available biological databases and computational tools. The workflow included gene annotation, coding sequence analysis, protein characterization, structural prediction, protein–protein interaction analysis, functional enrichment, disease association studies, therapeutic target exploration, and cancer expression profiling. Collectively, the analyses provide a detailed overview of PTEN structure, function, molecular interactions, and clinical significance while demonstrating the application of modern bioinformatics approaches in molecular biology research. 
Introduction
PTEN is located on chromosome 10q23.31 and encodes a dual-specificity phosphatase that primarily converts phosphatidylinositol (3,4,5)-trisphosphate (PIP₃) into phosphatidylinositol (4,5)-bisphosphate (PIP₂). Through this activity, PTEN negatively regulates the PI3K/AKT signalling pathway, thereby controlling cell proliferation, apoptosis, migration, metabolism, and survival. Alterations in PTEN are frequently associated with hereditary disorders and numerous cancers, including glioblastoma, breast, prostate, and endometrial cancers. Consequently, PTEN represents one of the most important tumour suppressor genes studied in cancer biology and precision medicine. 
Objectives
The primary objective of this project was to perform a systematic computational characterization of the human PTEN gene and protein using publicly available bioinformatics resources. Specific objectives included:
Gene annotation and transcript identification.
Coding sequence and ORF analysis.
Protein sequence characterization.
Physicochemical property analysis.
Conserved domain identification.
Secondary and tertiary structure prediction.
Protein–protein interaction analysis.
Gene Ontology and pathway enrichment.
Disease-associated variant analysis.
Therapeutic target exploration.
Pan-cancer gene expression and survival analysis. 
Bioinformatics Workflow
The study followed a sequential computational workflow beginning with retrieval of PTEN genomic information from NCBI Gene and RefSeq databases. The canonical protein sequence was analysed using ExPASy ProtParam to determine physicochemical properties, followed by conserved domain identification using the Conserved Domain Database (CDD). AlphaFold and DSSP were employed to investigate tertiary and secondary structural characteristics. STRING was used to construct the protein–protein interaction network, while ShinyGO and Reactome were applied for functional enrichment analyses. OMIM and ClinVar provided disease and variant information, the Therapeutic Target Database (TTD) was used to examine therapeutic relevance, and GEPIA3 enabled pan-cancer expression profiling and survival analysis. 
Databases and Tools
The project integrated fifteen major bioinformatics resources:
Database / Tool
Purpose
NCBI Gene
Gene annotation
Genome Data Viewer
Chromosomal visualization
RefSeq
Transcript and CDS retrieval
UniProt
Protein sequence
ORF Finder
Open Reading Frame identification
ExPASy ProtParam
Physicochemical analysis
Conserved Domain Database
Domain identification
AlphaFold
Three-dimensional structure
DSSP
Secondary structure
STRING
Protein interaction network
ShinyGO
GO and KEGG enrichment
Reactome
Pathway analysis
OMIM & ClinVar
Disease association and variants
Therapeutic Target Database
Therapeutic relevance
GEPIA3
Expression and survival analysis
Major Findings
The canonical PTEN transcript (NM_000314.8) encodes a 403-amino-acid protein (NP_000305.3) containing a catalytic phosphatase domain and a C2 membrane-binding domain. Physicochemical analysis identified PTEN as an acidic, hydrophilic protein with a molecular weight of approximately 47.17 kDa and a theoretical isoelectric point of 5.94. Structural analysis demonstrated a well-defined catalytic core together with a flexible C-terminal regulatory region.
Protein interaction analysis identified PTEN as a central hub interacting with proteins involved in PI3K/AKT signalling, tumour suppression, cell adhesion, and apoptosis. Functional enrichment analyses highlighted pathways regulating cell growth, migration, metabolism, immune responses, and cancer development, reinforcing PTEN's established biological role. 
Disease association studies demonstrated strong links between PTEN mutations and hereditary cancer syndromes, including PTEN Hamartoma Tumour Syndrome, Cowden syndrome, glioblastoma, prostate cancer, melanoma, and endometrial carcinoma. ClinVar analysis further revealed numerous pathogenic and likely pathogenic variants distributed throughout the coding region. 
Gene expression and survival analyses indicated that PTEN expression varies among different cancer types and that altered PTEN expression may possess prognostic significance depending on tumour type.
Conclusion
This project demonstrates how publicly available bioinformatics databases and computational tools can be integrated into a comprehensive workflow for the molecular characterization of a clinically important human gene. The analyses confirmed the structural organisation, functional domains, molecular interactions, signalling pathways, disease associations, and therapeutic relevance of PTEN. Beyond providing biological insights into one of the most significant tumour suppressor genes, the project highlights the value of computational biology in supporting hypothesis generation and guiding future experimental investigations.
Future Scope
Future work may expand this project through comparative genomics, phylogenetic analysis, molecular docking of PTEN with small-molecule inhibitors or activators, molecular dynamics simulations, transcriptomic integration using RNA-seq datasets, and machine learning approaches for predicting variant pathogenicity. Incorporating reproducible analysis scripts in Python or R would further strengthen the computational framework and improve reproducibility.
