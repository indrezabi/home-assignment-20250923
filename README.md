# Data Quality Analysis

## Project Overview

This project analyzes URL metadata and reputation signals to uncover mismatches, redirect behavior, and service-level inconsistencies. The goal is to improve data quality and threat detection logic.

## Workflow Summary

- **Data download** from Nord Security’s AWS access  
- **Python (Google Colab)** used for inspection, cleaning, and enrichment. Link: https://colab.research.google.com/drive/1z7b6UJZb0glY0I2ThFn6iDY8MSU0Un9V?usp=sharing 
- **CSV export** of cleaned data  
- **Looker Studio dashboard** built for final analysis and visualization. Link: https://lookerstudio.google.com/reporting/a2b9684c-1f70-4499-aa93-029c4e8418c6 
- **Conclusions, recommendations, and further ideas** presented directly in the dashboard

## Data Access Note

To run the Colab notebook, manually upload the original data files provided by Nord Security.  
Due to size limits, files were imported from local storage (not cloud).

Looker report defaults to data from 2015 onward, to exclude legacy records and prevent outdated entries (e.g., from 1936, etc) from skewing the analysis.

