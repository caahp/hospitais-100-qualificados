# Data Exploration - Quality Factor 100% Hospitals (ANS)

## Project Overview

This repository contains an exploratory analysis of the dataset **"Quality Factor – 100% Hospitals"**, published by the **Brazilian National Supplementary Health Agency (ANS)** on the open data portal ([dataset link](https://dados.gov.br/dados/conjuntos-dados/descontinuado-fator-de-qualidade---hospitais-100)).

The Quality Factor is a financial adjustment tool applied to healthcare providers (hospitals) based on quality criteria. This specific dataset lists hospitals that received **100% of the Quality Factor** during the period when ANS conducted these verifications (prior to 2018).

The goal of this project is to **analyze the geographic and statistical distribution of these hospitals**, using descriptive statistics and data visualization techniques.

---

## Repository Structure

- `Fator_Qualidade_Hospitais.csv` : Original CSV dataset (100% Hospitals).  
- `notebook.ipynb` : Notebook containing all analyses, statistics, and visualizations.  
- `README.md` : Project documentation.

---

## Analyses Performed

1. **Initial Dataset Exploration**
   - Preview of first rows
   - Data types
   - Missing values check

2. **Descriptive Statistics**
   - Count of hospitals by state (UF)
   - Mode, median, maximum, minimum, standard deviation, IQR
   - CNES and CNPJ duplicate check

3. **Visualizations**
   - Bar chart: number of 100% Quality Factor hospitals by state (UF)
   - Histogram of hospital distribution by state
   - Distribution by **region** (North, Northeast, Central-West, Southeast, South)
   - Pie chart showing the percentage of hospitals by region

4. **Interpretation**
   - States with the highest and lowest concentration of qualified hospitals
   - Geographic distribution of providers by region

---

## Technologies and Libraries

- Python 3  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Google Colab (execution environment)

---

## How to Run

1. Open the `notebook.ipynb` in Google Colab or Jupyter Notebook.  
2. Ensure the file `Fator_Qualidade_Hospitais.csv` is in the same folder or upload it to Colab.  
3. Run the cells to generate tables, statistics, and charts.

---

## Notes

- This dataset was **discontinued** in 2018 because ANS stopped publishing the list of qualifying hospitals, transferring verification to the operators.  
- The analyses here represent a **historical snapshot** of the period when the data was publicly available.
