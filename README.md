# Bangladesh Medicine Dataset Analysis

This repository contains an analysis of a medicine dataset obtained through web scraping. The analysis explores various aspects of the dataset, providing insights into pharmaceuticals, dosage descriptions, generic names, pharmaceutical companies, and retail prices.

## Dataset Overview

The dataset used in this analysis comprises information related to medicines, including brand names, dosages, generic names, pharmaceutical companies, and retail prices.

## Analysis Highlights

1. **Pharmaceutical Companies:**
   - Identification of top pharmaceutical companies based on the number of unique medicines produced.
   - Visual representation of the distribution of medicines among the top pharmaceutical companies.

2. **Dosage Descriptions:**
   - Identification of medicines with multiple dosage descriptions.
   - Exploration of the top medicines with multiple dosage descriptions.

3. **Generic Names:**
   - Analysis of the most common generic names in the dataset.
   - Identification of pharmaceutical companies producing the most unique generic names.

4. **Retail Prices:**
   - Overview of the distribution of retail prices for allopathic medicines.
   - Identification of medicines with specific dosage descriptions and their corresponding retail prices.

## Methodology

The analysis was conducted using Python and popular data analysis libraries such as Pandas, Matplotlib, and Seaborn. The dataset was cleaned, filtered, and visualized to derive meaningful insights.

## Web Scraping

The dataset was obtained through web scraping techniques. The process involved extracting relevant information from online sources to compile a comprehensive dataset for analysis.

## Repository Structure

- **datasets/:** 
  - `.json`: Contains the raw and processed medicine datasets in JSON format.
  
- **notebooks/:**
  - `dgda-medicine-dataset-analysis.ipynb`: Jupyter notebook used for data analysis.
  - `web-scrapping-medicines-dgda.ipynb`: Python scripts for web scraping and data preprocessing.
  - `medicine-dataset-analysis-report.ipynb`: Visualizations and report generated during the analysis.
