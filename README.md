# Inference Simulations (Psych 201a)

This repository contains in-class exercises for Psych 204, featuring simulations and data manipulation using R and the tidyverse.

The Quarto Markdown document ch6_tea_simulations.qmd accompanies the Inference lecture from Psych 201a and guides you through key tasks related to statistical inference simulations, providing hands-on experience with data simulation and analysis.

## Table of Contents
1. [Installation](#installation)
2. [Usage](#usage)
3. [Simulations Overview](#simulations-overview)
4. [Exercises](#exercises)
5. [License](#license)

## Installation

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/e-garzaelorduy/psych204_inclass_exercises.git
    ```
2. Install the required R packages by running the following in your R console:
    ```r
    install.packages("tidyverse")
    install.packages("ggplot2")
    install.packages("ggthemes") # optional, for enhanced plotting
    ```

## Usage

This project is intended to be run in **Quarto** to render the document into HTML format. If you haven't installed Quarto yet, you can find the installation guide [here](https://quarto.org/docs/get-started/).

To render the document, run the following command in your terminal:

```bash
quarto render ch6_tea_simulations.qmd --to html
