# Group-11-pips
This is our shared repository for the pips course group project 2026. 

## Citation
> Prado Nunes, R., Dzanic Arnaez, I., & Mauch, L. (2026). group-11-pips (will be modified) (Version 1.0.0) [Computer software]. https://github.com/lesliem17/group-11-pips

## Getting started
Clone the repository in RStudio:

```bash
git clone https://github.com/lesliem17/group-11-pips.git
```

### R
The R variant requires R 4.6.1 or newer and RStudio is recommended.

Install the relevant packages by running the following code.
```r
install.packages(c("plotly", "tidyverse", "ggplots2", "viridis", "rstatix"))
```
Open **main.pips11.qmd** in Rstudio and and run its chunks from top to bottom.  

## Repository Structure

```text
group-11-pips/
├── data/                   # Dataset files
├── .gitignore              # Files that should be ignored by Github
├── CITATION.cff            # Citation
├── LICENSE                 # MIT Projecticense
├── README.md               # Project documentation
├── group-11-pips.Rproj     # RStudio project file
└── main.pips11.qmd         # Main Quarto file
```

## Using the project

1. Clone the repository from Github onto your local hardware.
2. Open the project in RStudio.
3. Install the necessary R packages (by running the above mentioned code).
4. Make sure that the data files are stored in the adequate locations.
5. Open main.pips11.qmd in RStudio
6. Render the Quarto document to generate the report. Click render in the top bar (the blue arrow), or run
> quarto render main.pips11.qmd
in the terminal.

## Dependencies

- **R** — needed to run the analysis.
- **RStudio** — aids in running the code.
- **Quarto** — renders the report.

## References
### The Dataset
Abir, M. I. H. (n.d.). *Psychosocial dimensions of student life* [Data set]. Kaggle. https://www.kaggle.com/datasets/mdismielhossenabir/psychosocial-dimensions-of-student-life
