# Description
This repository contains all the materials to reproduce the manuscript.

To render only the manuscript, run:

```bash
quarto render manuscript.qmd
```

# Repository structure

```text
power_manuscript/
├── data/                             # Data used in the analyses
│   ├── psychsci.rds                  # Articles used to run the Metacheck modules
│   ├── res_power.RData               # Results of the `power` module using the rule-based approach
│   └── res_power_llm.RData           # Results of the `power` module using the LLM-based approach
│
├── manuscript.qmd                    # Quarto manuscript source file
├── _quarto.yml                       # Quarto project configuration
├── references.bib                    # Bibliography file containing references
├── package-citations.bib             # Bibliography file containing references
├── _extensions/                      # Quarto extensions used by the manuscript
├── apa.csl                           # APA citation style file
│
├── output/                           
│   └── manuscript.html               # Rendered manuscript   
│               
│             
│ 
└── session-info.txt                  # R session information
```

