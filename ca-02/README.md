# Data Mining Assignment 2

## Overview

This assignment covers frequent itemset mining and association rule learning on two datasets:

- Movies dataset (movies.csv): contains movie titles and genres
- Ratings dataset (ratings.csv): contains user ratings for movies 

## Contents

The Jupyter notebook contains the following:

### Data Preprocessing

- Merging movies and ratings datasets
- Filtering out movies with few ratings

### Frequent Itemset Mining

- Encoding movie titles into binary columns  
- Finding frequent itemsets using apriori and FP-growth algorithms
- Varying minimum support threshold

### Association Rule Learning

- Generating rules from frequent itemsets
- Varying minimum confidence threshold
- Analyzing and interpreting the rules

## Requirements

The following Python libraries are used:

- Pandas
- Matplotlib  
- Seaborn
- MLXTEND (apriori, fpgrowth, association_rules)

## Usage 

To use this notebook:

1. Clone this repository 
2. Download the movies.csv and ratings.csv datasets
3. Place the datasets in a data folder
4. Run the Jupyter notebook

The notebook contains detailed explanations and visualizations for the frequent pattern mining and association rule learning tasks.
