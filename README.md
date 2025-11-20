## QML Notebook Analysis
# Overview
This Jupyter Notebook (qml.ipynb) performs an analysis on a malware dataset, including data exploration, visualization, and some basic machine learning preprocessing steps.....

## Contents
 1. Setup and Data Loading
Installs necessary packages (seaborn)

Imports required libraries:

1. matplotlib for visualization
2. sklearn for preprocessing
3. numpy and pandas for data manipulation
4. seaborn for advanced visualizations

2. Data Exploration
Loads the malware dataset (Malware_dataset.csv) with 10,000 rows and 35 columns

Displays the first 5 rows of the dataset

Lists all column names in the dataset

3. Visualization Functions
Defines plotPerColumnDistribution() function to visualize distributions of columns with less than 50 unique values

# Creates histograms for numerical columns and bar plots for categorical columns

4. Dataset Characteristics
The dataset contains:

Malware classification data

System performance metrics (CPU priority, memory usage, etc.)

Process statistics (usage counters, faults, etc.)

## Key Features
Performs basic exploratory data analysis

Includes visualization capabilities for data understanding

Prepares data for potential machine learning applications

## Usage
Ensure required packages are installed

Run cells sequentially to:

Load and explore the data

Generate visualizations

Prepare data for further analysis

## Requirements
1. Python 3.x
2. Jupyter Notebook

# Libraries:

1. pandas
2. numpy
3. matplotlib
4. seaborn
5. scikit-learn

## Dataset
The analysis uses Malware_dataset.csv which contains:

10,000 samples

35 features

Binary classification (malware vs benign)

Note: The notebook only loads the first 10,000 rows of what appears to be a larger dataset (100,000 rows mentioned in a comment).

## How to run
1. Clone the repo
```
git clone https://github.com/WizHabasi/QML.git
```
2. Navigate to the directory
```
cd QML
```
3. Install the dependencies
