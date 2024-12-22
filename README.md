# Master's Thesis Data Analysis

This repository contains the code and data used for the analysis in my Master's thesis. The project involves two primary data sources:

1. **Task 1:** Participant prompts and responses.
2. **Task 2:** Participant survey responses.

## Repository Structure

- **`Research Data/`**  
  Contains all participant prompts and responses for Task 1. No personally identifiable information (PII) is included.
  
- **`Task2Responses.csv`**  
  Contains survey data for Task 2. All data is anonymized.

## Instructions

To reproduce the analysis, run the Jupyter notebooks in the following order:

1. `LexicalAnalysis.ipynb`  
   Performs lexical analysis on the Task 1 data.

2. `Readability.ipynb`  
   Analyzes readability metrics for the Task 1 data.

3. `LanguageTool_check.ipynb`  
   Uses LanguageTool to check for grammar and language issues in participants' prompts.

4. `Task2ResponsesAnalysis.ipynb`  
   All the other data processing, calculations, analysis and visualizations described in the thesis.

## Notes

- The repository includes only anonymized and non-PII data.
- The analysis was conducted using Python version 3.11.5 and Jupyter Notebooks.

Feel free to use the code to validate the work done in the thesis.
