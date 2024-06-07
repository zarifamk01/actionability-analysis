# Actionability Analysis

## Overview

This repository contains Jupyter Notebook files for analyzing biological data with a focus on actionability, particularly related to the NTRK1 gene. The project involves parsing datasets, generating visualizations, querying biological databases, and performing various analyses to explore actionable insights in biological data.

## Steps

### 1. Data Parsing and Visualization
- **Objective**: Parse the actionability file, filter data related to the NTRK1 gene, and create visualizations.

### 2. Protein Sequence Retrieval
- **Objective**: Retrieve fasta sequences from the protein database for the NTRK1 gene.

### 3. Database Querying
- **Objective**: Query databases such as KEGG and UniProt for pathway and protein information related to NTRK1.

### 4. PubMed References
- **Objective**: Fetch PubMed references related to the NTRK1 gene.

### 5. Additional Analysis
- **Objective**: Perform additional analyses, such as filtering data based on specific conditions and visualizing pathways.


## Summary

For this project, we initiated by setting up the necessary libraries and organizing the project files. We parsed the actionability file, focusing on the search term NTRK1, and created a new dataset called `filtered_df` containing relevant columns. We then generated visualization charts, including scatterplots, bar graphs, and histograms, to illustrate relationships between specific columns. After initiating BioPython sessions to search the database for NTRK1 and fetching fasta sequences and PubMed references, we used bioservices to access KEGG and UniProt databases to retrieve specific information, including pathways, protein names, and family domain names for the assigned search term.

## Dependencies

- pandas
- matplotlib
- seaborn
- numpy
- bioservices
- biopython

## Usage

1. Clone the repository:git clone https://github.com/yourusername/actionability-analysis.git

2. Navigate to the directory:cd actionability-analysis

3. Open and run the Jupyter Notebooks using Jupyter Notebook or JupyterLab to explore the analysis and results.



