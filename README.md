# Collaboration in the Canadian Disability Community: A Social Network Analysis

This project uses social network analysis to explore patterns of collaboration among participants in Canada's disability community. The initial analysis was conducted by Dr. Derrick Cogburn in support of Dr. Keiko Shikako at McGill University, and Dr. Linda Nguyen at the University of Calgary. The analysis is based on survey data collected in both French and English, reflecting the bilingual nature of the community and its organizations. All data has been de-identified, and anonimized.

## Overview

The project examines how individuals and organizations within the disability community connect, collaborate, and share resources. Using a combination of R and Python within a Quarto workflow, the analysis produces a report that visualizes and interprets the structure of these collaborative networks.

## Project Structure

```
├── _quarto.yml
├── data/               # Cleaned survey data (CSV)
├── R/                  # R scripts for analysis
├── python/             # Python scripts for analysis
├── reports/            # Main reports as PDF and html
├── figures/            # Collection of figures generated during analysis
└── README.md
```

## Requirements

- [Positron](https://positron.posit.co/) or another IDE with Quarto support
- [Quarto](https://quarto.org/) (latest version recommended)
- **R** with relevant network analysis packages (e.g., `igraph`, `tidygraph`, `ggraph`)
- **Python** with relevant packages (e.g., `networkx`, `pandas`)

## Data

The analysis draws on a cleaned CSV dataset derived from a bilingual (French/English) survey administered to participants in the Canadian disability community. The survey captures information about collaborative relationships between individuals and organizations.

Raw and personally identifiable data are excluded from this repository. Only the cleaned, de-identified SNA datasets are included.

## Contact

**[Your Name]**
Dr. Derrick Cogburn, dcogburn@american.edu/dcogburn@praxisanalytics.net
