# Lithuanian Statistics Internship Project

This repository contains all the code and materials I developed during my internship at Lithuanian Statistics. The primary objective of my internship was to create a training platform for in-house training on R, as the organization transitioned from SAS to R. These resources are designed to help employees become proficient in R and include a series of tutorials developed using the `LearnR` package. 

## Table of Contents

- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Data](#data)
- [Tutorial Structure](#tutorial-structure)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Introduction

As Lithuanian Statistics moved from using SAS to R for data analysis, I was tasked with developing a comprehensive in-house training platform to facilitate this transition. The training materials are structured as interactive tutorials created using the `LearnR` package. These tutorials are designed to guide users through the fundamentals of R, focusing on the specific needs of the organization.

## Project Overview

The repository is structured to support a smooth transition from SAS to R. The project includes:

- **R Scripts**: All the code developed during the internship.
- **Interactive Tutorials**: Four main parts that cover the essential aspects of R programming.
- **Anonymized Data**: Datasets in `.xlsx` format that have been anonymized for training purposes.

## Data

The data used in these tutorials has been anonymized to protect sensitive information. The datasets are provided in Excel (`.xlsx`) format and are used throughout the tutorials to provide practical, hands-on experience with R.

## Tutorial Structure

The training platform is divided into four main parts:

1. **Introduction to R**: Covers the basics of R, including installation, the RStudio environment, basic syntax, and data types.
   
2. **Data Manipulation**: Introduces key R packages like `dplyr` and `tidyr` for data wrangling, including filtering, transforming, and summarizing data.

3. **Data Visualization**: Focuses on creating visualizations using `ggplot2`, including scatter plots, bar charts, histograms, and more advanced plots.

4. **Statistical Analysis**: Guides users through basic statistical tests, regression analysis, and interpreting results in R.

Each tutorial is interactive, allowing users to write and execute R code within the platform, providing immediate feedback and reinforcing learning.

## Usage

To use these materials:

1. **Clone the repository** to your local machine.
2. **Install the necessary R packages** (see [Dependencies](#dependencies) below).
3. **Load the tutorials** using the `LearnR` package, and follow along with the interactive instructions.
4. **Explore the data** using the provided `.xlsx` files.

These tutorials are designed to be self-paced, allowing users to progress at their own speed.

## Dependencies

The tutorials and scripts in this repository require R and the following R packages:

- `LearnR`
- `tidyverse`
- `readxl`
- `ggplot2`
- `dplyr`
- `tidyr`

Install the required packages using:

```r
install.packages(c("LearnR", "tidyverse", "readxl", "ggplot2", "dplyr", "tidyr"))
