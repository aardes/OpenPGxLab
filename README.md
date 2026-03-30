# OpenPGxLab

**OpenPGxLab** is an open learning and development hub for **pharmacogenomics (PGx)**, covering biological foundations, sequencing technologies, bioinformatics pipelines, HLA, annotation resources, and clinical interpretation.

This project is being built as a community-oriented space for learning, teaching, and developing practical PGx knowledge from basic concepts to advanced implementation.

## Why OpenPGxLab?

Pharmacogenomics sits at the intersection of:

- pharmacology
- genetics
- bioinformatics
- clinical decision support
- sequencing technology
- population genomics

While many PGx resources focus only on high-level clinical summaries, OpenPGxLab aims to connect the full stack:

- **biology**
- **genotype-to-phenotype interpretation**
- **testing technologies**
- **bioinformatics**
- **annotation databases**
- **clinical reporting and implementation**

## Project Goals

OpenPGxLab aims to:

- provide a structured PGx learning path from beginner to advanced
- explain both clinical and technical aspects of PGx
- compare technologies used for PGx testing, including panel-based assays, SNP arrays, WES, WGS, short-read, and long-read sequencing
- cover the role of **HLA** in drug hypersensitivity and immune-mediated PGx
- explore the databases and knowledge resources needed for annotation and decision-making
- support hands-on learning through examples and exercises
- build an open community resource that others can contribute to

## Target Audience

This repository is intended for:

- bioinformaticians
- clinical geneticists
- molecular biologists
- pharmacologists
- laboratory scientists
- software developers working in genomics
- students and researchers interested in PGx
- clinicians who want a deeper technical understanding of PGx

## Planned Course Structure

### 1. Foundations of PGx
- What PGx is and what it is not
- Pharmacogenetics vs pharmacogenomics
- Pharmacokinetics vs pharmacodynamics
- Drug efficacy, toxicity, and adverse reactions
- Core examples and intuition

### 2. Core PGx Genes and Mechanisms
- CYP enzymes
- Prodrugs vs active drugs
- Transporters and target genes
- Major PGx genes
- Phenoconversion and drug-drug interactions

### 3. HLA and Immune-Mediated PGx
- Why HLA matters in PGx
- Hypersensitivity mechanisms
- Severe adverse drug reactions
- HLA typing and interpretation challenges

### 4. Genotype-to-Phenotype Interpretation
- Variants, haplotypes, diplotypes, and star alleles
- Activity score systems
- Metabolizer categories
- Rare and uncertain alleles
- Interpretation limitations

### 5. PGx Testing Technologies
- Targeted PGx panels
- SNP arrays
- Whole exome sequencing (WES)
- Whole genome sequencing (WGS)
- Short-read sequencing
- Long-read sequencing
- Strengths, weaknesses, and use cases

### 6. PGx Bioinformatics
- PGx-oriented bioinformatics pipelines
- SNVs, indels, CNVs, and structural variants
- Haplotype and star allele calling
- Difficult loci such as CYP2D6
- HLA typing approaches
- Technology-specific analysis challenges

### 7. Annotation Databases and Decision Support
- PharmGKB
- CPIC
- DPWG
- PharmVar
- ClinVar and complementary resources
- Population databases
- Local annotation and decision-support design

### 8. Clinical Reporting and Implementation
- From genotype to prescribing recommendation
- Actionable vs non-actionable findings
- Contraindications, dose changes, and alternatives
- Reporting strategy
- Integration into clinical workflows

### 9. Population-Specific and Real-World PGx
- Population differences in allele frequencies
- Underrepresented populations in PGx
- Building region-aware PGx resources
- Validation and implementation considerations

### 10. Advanced Topics and Future Directions
- Oncology PGx vs somatic precision oncology
- AI-assisted PGx interpretation
- Platform design for PGx
- Future applications and research directions

## Hands-On Component

This repository is also intended to include practical material such as:

- case-based PGx interpretation exercises
- technology selection exercises
- genotype-to-phenotype conversion examples
- HLA-associated drug risk examples
- annotation workflow examples
- bioinformatics design exercises
- small prototype tools and scripts where relevant

## Repository Structure

Planned structure:

```text
OpenPGxLab/
├── README.md
├── docs/
│   ├── index.md
│   ├── roadmap.md
│   ├── glossary.md
│   ├── modules/
│   └── exercises/
├── assets/
│   ├── images/
│   └── diagrams/
├── examples/
├── tools/
└── CONTRIBUTING.md
```

## Current Status

OpenPGxLab is currently in its early development phase.

The initial focus is on:

- defining the learning roadmap
- building the core educational materials
- organizing the repository structure
- preparing practical exercises
- shaping the project for future public release and collaboration

## Contributing

Contributions, suggestions, and corrections are welcome.

In the future, contributors may help with:

- improving explanations
- adding examples and diagrams
- reviewing scientific and technical accuracy
- expanding exercises
- improving bioinformatics workflows
- extending annotation and reporting sections

A dedicated `CONTRIBUTING.md` file will be added as the project grows.

## Vision

The long-term goal of OpenPGxLab is to become a practical, open, and technically strong PGx resource that helps bridge:

- education and implementation
- biology and bioinformatics
- sequencing data and clinical decisions
- individual learning and community contribution

## Author

Initiated as an open learning and community project in pharmacogenomics.

---

**OpenPGxLab**  
*Open pharmacogenomics learning, bioinformatics, and clinical decision-support resources.*
