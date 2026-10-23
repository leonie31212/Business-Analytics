# mgh-dbm25-group04-ski-resorts

## Authors
- Anna Sophie Gutzmann
- Leonie Horwege

## Project Title
**Analysis of European Ski Resorts: Prices, Size and Resort Types**

## Project Description
This project analyzes a dataset of 376 European ski resorts containing information as of February 2022. The aim is to investigate the relationship between ski resort characteristics and daily ski pass prices.

The analysis focuses on price differences in relation to resort size, comparisons between selected European countries, factors associated with daily prices, and the identification of different ski resort types. The results are explored using data analysis, visualizations and statistical or machine learning methods where appropriate.

## Research Questions

The project addresses the following four research questions:

1. **Price and resort size:** Are larger ski resorts cheaper per kilometer of ski slopes?
2. **Comparison between countries:** Do daily ski pass prices differ between Austria, France, Switzerland and Italy when comparing ski resorts in the same size category?
3. **Factors influencing prices:** Which variables best explain daily ski pass prices? The variables considered include slope length, elevation, vertical drop, the proportion of difficult slopes and country.
4. **Ski resort types:** Which types of ski resorts can be identified, and which resorts are unusually inexpensive or expensive compared with other resorts of the same type?

## Problem Statement and Objectives

European ski resorts differ in size, terrain, location and available facilities. These differences may be associated with variations in daily ski pass prices. However, it is not immediately clear whether larger resorts offer better value for money or how prices compare between countries when resort size is taken into account.

The objective of this project is to examine these relationships using the available dataset. By comparing prices, investigating relevant variables and categorizing ski resorts, the project aims to provide a better understanding of price differences between European ski resorts.

## Dataset

The dataset contains information on 376 European ski resorts as of February 2022.

The analysis considers information related to:
- Daily ski pass prices
- Length of ski slopes
- Elevation and vertical drop
- Distribution of ski slopes by difficulty
- Country

The dataset is provided as a CSV file named `European_Ski_Resorts.csv`.

## Methods

The analysis uses several approaches to investigate the research questions:

- **Price per kilometer:** Daily ski pass prices are related to the total length of ski slopes. Resorts are compared across different size categories.
- **Country comparison:** Daily ski pass prices are compared between Austria, France, Switzerland and Italy while accounting for resort size categories.
- **Feature importance:** A Random Forest model is used to examine the relative importance of selected variables for predicting daily ski pass prices.
- **Resort categorization:** Ski resorts are assigned to types based on predefined rules relating to the distribution of slopes by difficulty. Prices are then compared within these categories to identify relatively inexpensive or expensive resorts.

The analyses and visualizations are documented in the Jupyter Notebook.

## Quick Start

The project was developed using Google Colab.

1. Download `Skiresorts.ipynb` from this repository.
2. Open [Google Colab](https://colab.research.google.com/).
3. Upload the notebook to Google Colab.
4. Upload `European_Ski_Resorts.csv` to the Colab session.
5. Check that the file path in the notebook matches the uploaded CSV file.
6. Run the notebook cells from top to bottom.

If the notebook requires additional Python packages, install them in the Colab session as needed.

## Repository Contents

- `README.md` – Project description, research questions, methods and instructions for running the analysis.
- `Skiresorts.ipynb` – Jupyter Notebook containing the analysis, code and visualizations.
- `European_Ski_Resorts.csv` – Dataset containing information about European ski resorts.

