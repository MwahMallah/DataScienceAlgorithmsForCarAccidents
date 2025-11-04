# Data Science Algorithms for Car Accidents

This repository contains a collection of **Data Science algorithms applied to car accident datasets**. The goal of this project is to analyze traffic data, identify patterns, and build predictive models to better understand and prevent car accidents. These algorithms were developed as part of a **bachelor's thesis project**.

## Project Overview

The project includes:

- Data preprocessing and cleaning
- Exploratory data analysis (EDA)
- Various machine learning algorithms for prediction and classification
- Visualization of results and insights from traffic datasets

## Implemented Algorithms

### Classifier

A **Random Forest classifier** is implemented to predict outcomes related to car accidents based on available features.

### Clusterizer

A **DBSCAN-based clusterizer** is used to identify high-risk areas by detecting accident clusters with many incidents. Only the largest clusters are considered, providing coordinates and approximate radius for each dangerous zone.

## Datasets

The repository contains example datasets (CSV files) that include traffic and accident data. These datasets are used to train and test the machine learning models.

## Getting Started

To run the algorithms:

1. Clone the repository:
   ```bash
   git clone https://github.com/MwahMallah/DataScienceAlgorithmsForCarAccidents.git
   ```
2. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```
3. Create a folder data/ in the project root and add the CSV file brno_nehody.csv from [Czech Police accident statistics](https://policie.gov.cz/clanek/statistika-nehodovosti.aspx?q=Y2hudW09Mg%3d%3d)
4. Run the Python scripts in the repository to perform analysis and predictions.
