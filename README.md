# DSCI 521 Milestone 3

This repository contains my Quarto website for DSCI 521 Milestone 3. The website includes computational posts written in both Python and R.

## Prerequisites

The project uses:

- Quarto
- Python 3.14
- uv
- R 4.6
- renv

## Reproducing the environment

Clone the repository and enter the project directory:

```bash
git clone https://github.com/LaithNidal/LaithNidal.github.io
cd DSCI-521_MileStone_2-
```

Restore the Python environment:

```bash
uv sync
```

Restore the R environment by starting R:

```bash
R
```

Then run:

```r
renv::restore()
```

Exit R after the packages have been restored.

## Building the website

From the top-level directory of the repository, run:

```bash
uv run quarto render
```

The rendered website is written to the `docs/` directory.

## Data

The computational posts use the Palmer Penguins dataset from the `palmerpenguins` packages available for Python and R.

Dataset information: https://allisonhorst.github.io/palmerpenguins/

An internet connection is required when initially restoring the Python and R environments.