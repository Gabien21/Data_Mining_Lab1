# Data Mining Lab - Data Preprocessing 
## Overview
This repository contains the Jupyter Notebook for the Data Mining lab at the University of Science, Vietnam National University Ho Chi Minh City (VNUHCM) for the academic year 2023-2024.

## Table of Contents
1. [Introduction](#introduction)
2. [Import Libraries](#import-libraries)
3. [Exploring Your Data](#exploring-your-data)
4. [Data Type Analysis](#data-type-analysis)
5. [Discretization Techniques](#discretization-techniques)
6. [Outlier Handling Techniques](#outlier-handling-techniques)
7. [Feature Scaling Techniques](#feature-scaling-techniques)
8. [Usage](#usage)

## Introduction
This notebook provides a comprehensive guide on data preprocessing techniques including data exploration, handling missing values, encoding categorical variables, discretization, outlier detection, and feature scaling.

## Import Libraries
Before starting, ensure you have the necessary libraries installed:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

Or, if using Jupyter Notebook:

```python
!pip install numpy pandas scikit-learn matplotlib seaborn
```

## Exploring Your Data
- Read raw data from file
- Check the number of rows and columns
- Understand the meaning of each row
- Detect duplicate rows
- Identify column meanings

## Data Type Analysis
- Convert datatype for UCT times attribute
- Explore datetime attributes
- Explore numerical attributes
- Explore non-numerical attributes
- Encode categorical variables

## Discretization Techniques
- Equal Width Discretization
- Equal Frequency Discretization

## Outlier Handling Techniques
- Outlier Trimming
- Outlier Capping Using IQR
- Outlier Capping Using Mean & Standard Deviation
- Outlier Capping Using Quantiles

## Feature Scaling Techniques
- Standardization
- Min/Max Scaling
- Mean Normalization
- Maximum Absolute Scaling
- Median and Quantile Scaling
- Vector Unit Length Scaling
- When and where to apply normalization techniques

## Usage
1. Clone this repository:

   ```bash
   git clone https://github.com/Gabien21/Data_Mining_Lab1.git
   ```

2. Open the Jupyter Notebook:

   ```bash
   jupyter notebook data_pre_processing.ipynb
   ```

3. Run the cells step by step to perform data preprocessing operations.
