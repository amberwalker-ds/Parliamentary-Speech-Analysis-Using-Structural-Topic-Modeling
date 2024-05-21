# Parliamentary Speech Analysis Using Structural Topic Modeling

## Overview
This project involves an analysis of parliamentary speeches made by UK House of Commons legislators in 2014. I focus on how speech topics vary by the gender of the MP using structural topic modeling (STM).

## Key Components

### 1. Data Loading and Preparation
- Load and inspect the dataset (`hoc_speeches.Rdata`).
- Summarize the dataset to understand its structure.

### 2. Data Transformation
- Convert the data into a corpus object using the `quanteda` package.
- Pre-process the text data to create a document-feature matrix, including removing punctuation and numbers.

### 3. Structural Topic Modeling
- Run the STM using the `stm` package with gender as a covariate for topic prevalence.
- Estimate the model and visualize the topics.

### 4. Topic Analysis
- Identify the top words and top documents for each topic.
- Report findings and interpret the results in the context of parliamentary speech.

### 5. Effect of MP Gender
- Use the `estimateEffect` and `plot.estimateEffect` functions to analyze the influence of MP gender on topic usage.
- Highlight topics where gender differences are most pronounced.

## Libraries and Tools
- `quanteda`
- `topicmodels`
- `LDAvis`
- `stm`
- `knitr`
- `lda`
- `servr`

## Additional Resources
- [STM Paper](https://scholar.princeton.edu/files/bstewart/files/stmnips2013.pdf)
- [STM Vignette](https://cran.r-project.org/web/packages/stm/vignettes/stmVignette.pdf)
