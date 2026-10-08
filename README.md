# Analysis of the effect of PMM2 variants on PMM2-CDG

**Course:** Introduction to Bioinformatics · UPC · 2026-2027
**Group:** 12DP-A
**Authors:** Dàlia Jordan, Salomé Murillo, Noah Quixal, Elsa Rosado, Adriana Dotsenko

## Description

PMM2-CDG is a genetic disease caused by a deficiency of the enzyme phosphomannomutase 2 (PMM2). This enzyme is needed to build glycans (sugar chains that attach to proteins); without it, many proteins fail to function correctly, affecting several organs at once, especially the nervous system. This project studies the PMM2 protein sequence and structure and compares it with a pathogenic variant, to analyze how the changes affect the protein structurally and functionally and lead to the disease.

## General objective

Study the sequence of the protein PMM2 and compare it with its variant to analyze how the changes affect it structurally and functionally, leading to the disease (PMM2-CDG).

*(Source wording, `project_bioinfo_objectives.docx`: "Study the sequence of the protein PMM2 and compare it with its variant to analyse how the changes affect it structurally and functionally leading to the disease." - only the double space was removed, "analyse"->"analyze" for US spelling consistency with the rest of the document, and "(PMM2-CDG)" added since that's the disease being referred to.)*

## Specific objectives

The original brainstormed list had six overlapping objectives; they have been merged into four measurable ones for this README (exact original wording kept below for comparison - please check the merge is faithful to what was intended).

<details>
<summary>Before (6 objectives, exact original wording)</summary>

1. Study the protein structure of PMM2
2. Determine the changes that cause a variant
3. Visualize the sequence of the protein structure
4. Compare the sequences of PMM2 and its variant
5. Determine the changes that affect the structure and function of the protein which lead to a disease
6. Compare between differents species the sequences so to see the important parts of the sequence

</details>

**After (4 measurable objectives):**

1. Retrieve and visualize the reference PMM2 protein sequence and its 3D structure (UniProt, PDB, InterPro domains). *(merges 1 + 3)*
2. Identify the structural and functional changes introduced by the pathogenic variant and relate them to the PMM2-CDG disease mechanism. *(merges 2 + 5)*
3. Align and structurally superpose the reference and variant sequences to pinpoint the altered residues/regions. *(from 4)*
4. Compare PMM2 sequences across at least two orthologous species to identify conserved, functionally important regions. *(from 6)*

## Milestones

| ID | Milestone | Date |
|---|---|---|
| M1 | Github repository created | 17/09/2026 |
| M2 | Have the project defined | 09/10/2026 |
| M3 | Relevant research/scientific papers selected | 06/10/2026 |
| M4 | Theoretical biological background completed | 13/10/2026 |
| M5 | Have done the comparison with the variant | 19/10/2026 |
| M6 | Have analyzed the results and defined the conclusions | 22/10/2026 |
| M7 | Final scientific article submitted | 26/10/2026 |

Milestone wording is the exact original list from `project_bioinfo_objectives.docx` ("Github" kept lowercase as written there); only the dates are new, taken from the corrected Gantt chart ([`gant/v1_frozen_2026-10-09/gantt_v1.md`](gant/v1_frozen_2026-10-09/gantt_v1.md)), where the mapping from each milestone to the task(s) it's based on is documented. Please check M2-M6 map to the right tasks.

## Project members

Responsibilities and Background are reproduced in full from `project_bioinfo_objectives.docx` ("PROJECT MEMBERS AND ROLES"), with only spacing/capitalization fixes ("github" -> "GitHub", "Telecommunication" -> "Telecommunications", double spaces removed) - no sentences or clauses were shortened.

| Name | Role | Responsibilities | Background |
|---|---|---|---|
| Dàlia Jordan | Project Manager | Responsible for creating GitHub, tracks the project, distributes the tasks, makes sure deadlines are met, organizes meetings with the team, monitors the progress. | I come from a Higher Vocational Training in Web Application Development (DAW), and I have hands-on experience using bioinformatics tools. I have also coordinated projects with classmates using Gantt charts to plan tasks and deadlines. In addition, I completed a six-month internship in a research group, which gave me a clear understanding of the needs and working pace of a research project. |
| Salomé Murillo | Product Owner | Ensures that the final product meets the objectives, defines the goal of the project, defines the main ideas and requirements, guides the team towards the important ideas. | Before starting this degree, I did a first year in Telecommunications that gave me some knowledge in mathematics and programming. As a first year student my experience in bioinformatics is still at early stages so this would be one of my first opportunities to get in touch within the field. My prior technical background helps me approach the computational analysis of the data, while throughout the project I am expanding my knowledge of molecular biology and bioinformatics tools. |
| Noah Quixal | Bioinformatics Specialist | Analyzes and compares the structures of the proteins, makes comparisons of the sequences, visualizes and creates figures, interprets the evolution and the results. | My first contact with the Bioinformatics field was through the TdR. I used different computational tools to simulate and compare the evolution of two species under different conditions. In this sense I have a fair amount of experience with analysis of biological data, both in its interpretation and in creating material to explain it. However, this is the first time I do a project based on proteins and their sequencing, so I hope to gain a better understanding on the subject we're applying informatic tools on. |
| Elsa Rosado | Structural Analyst | Analyzes changes in structure of the protein and its variant, uses resources such as InterPro, UniProt to complement, compares the variant and its protein structures, studies the interactions of molecules, interprets the differences, redacts the abstract. | I have a good background in biology and I really enjoy learning about living organisms and biological processes. However, I have little experience with computers, so bioinformatics is a new field for me. I am interested in learning how computational tools can be used to study biological data. I hope to improve my computer skills and gain a better understanding of bioinformatics and GitHub. |
| Adriana Dotsenko | Biological Analyst | Defines the objectives, responsible for the research of the proteins and gene, studies the disease and its relationship, investigates the effects of the variant on the protein and function, and focuses on biological research. | Regarding the part of science I have experience in research and biology from high school. So I understand the concepts and have an interest in investigating more. I don't have any knowledge about programming. So I am looking forward to learning to use GitHub and understand how we can connect it with biology. |

## Repository structure

```
G12A_PMM2_CDG_IB_2026/
├── README.md                 - this file
├── .gitignore
├── report/
│   └── report.md             - BMC Bioinformatics-style report skeleton
├── status/
│   └── project_status.md     - task tracking table, updated up to 08/10/2026
├── gant/
│   ├── README.md             - explains frozen vs. live
│   ├── v1_frozen_2026-10-09/ - Gantt + risk analysis as submitted 09/10/2026
│   │   ├── gantt_v1.xlsx
│   │   ├── gantt_v1.png
│   │   ├── gantt_v1.md
│   │   └── risk_analysis.md
│   └── live/
│       └── gantt_live.xlsx   - kept up to date until 26/10/2026
├── references/                - bibliography (BMC format)
└── figures/                   - figures referenced in the report
```

See [`gant/`](gant/) for the Gantt chart and risk analysis, [`status/`](status/) for task tracking, and [`report/`](report/) for the manuscript.
