---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Work experience
======
* Postdoctoral researcher at MIGEVEC (IRD), Mar. 2026 – present
  * How placental malaria reshapes the transcriptional landscape of fetal cord-blood monocytes
  * Integrated multi-omics workflow (scRNA-seq/multiome, spatial transcriptomics, epigenomics, proteomics, metabolomics)
  * Reproducible R/Quarto analyses of a 58,000-cell multiome dataset (Seurat v5, SingleR)

* PhD student at Laboratoire Génome et Développement des Plantes (CNRS), Oct. 2022 – Nov. 2025
  * Annotation-free pipeline (Python, R, Bash, SLURM) screening 418 plant and 1,081 fungal genomes
  * 22 high-confidence inter-kingdom transfers, 21 of them from fungi to plants
  * A plant-derived DNA transposon that invaded a powdery mildew fungus and expanded to 172 MITE copies
  * First-author review in *The Plant Cell* (2025) and first-author preprint (2026)
  * MSc intern co-supervision and teaching

* Intern at Institut Sophia Agrobiotech (INRAE / CNRS / Univ. Côte d'Azur), Jan. – June 2022
  * Study of structural variants in plant-parasitic nematode genomes
  * Development of a pipeline and use of tools under SLURM cluster
  * Programming and scripting under Bash mainly

* Intern at Centre Méditerranéen de Médecine Moléculaire (INSERM), Feb. – July 2021
  * Bioinformatics analysis of leukemic cells by single-cell RNAseq approach
  * Programming and use of packages under R and Python (Seurat, SCENIC, Monocle...)
  * Mini-project of drug repositioning with CMap on SARS-CoV-2 (co-first author)

Education
======
* PhD in Biology, Université de Perpignan Via Domitia, 2025
* MSc in Life Sciences – Biology, Computer Science & Mathematics track (with honours), Université Côte d'Azur, 2022
* BSc in Life Sciences – Bioinformatics track, Université Côte d'Azur, 2020
* TULIP Summer School on Integrative Biology and Ecology, July 2023

Skills
======
* **Programming:** Python (pandas, scikit-learn), R (tidyverse, ggplot2, Quarto), Bash, SQL
* **Workflows/HPC:** Nextflow, Snakemake, Docker/Singularity, Git, SLURM
* **Single-cell & spatial:** Seurat v5, SingleR, Monocle 3, SCENIC, Squidpy, cell2location
* **Genomics/phylogenomics:** BWA-MEM2, Minimap2, DIAMOND, BEDTools, MAFFT, IQ-TREE 2, AUGUSTUS
* **Statistics & ML:** GLM, survival analysis, Bayesian statistics, random forest

Languages
======
* French (native)
* English (fluent, C1 – TOEIC 955/990)
* Spanish (limited working proficiency)

Publications
======
<ul class="ag-cv-list">{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
  
Talks
======
<ul class="ag-cv-list">{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>
  
Teaching
======
<ul class="ag-cv-list">{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
  
Outreach and service
======
* Author and volunteer reviewer, bioinfo-fr.net, a French-language bioinformatics blog for a general audience (2025 – present)
* IT manager of the PhD students association (UPVDoc) of the University of Perpignan (2022-2023)
* Doctoral and post-doctoral students' representative on the Laboratory Council (2023-2025)
* Doctoral students' representative on the doctoral school board (2023-2025)
* Scientific mediation workshop "DNA in all its states" at the science festival of Perpignan (Oct. 2022)
* DECLICS Ambassador : Scientific outreach for high school students (Nov. 2023)
* Scientific mediation workshop "PlantAdapt" at the science festival of Perpignan (Oct. 2024)
