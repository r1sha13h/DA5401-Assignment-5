Name: Rishabh Mishra
Roll: DA25M025
Date: 5 October 2025

# Assignment-5: Yeast Gene Expression Analysis

## Description
This Jupyter notebook analyzes a multi-label yeast gene expression dataset using dimensionality reduction techniques. It preprocesses data, creates simplified target categories, and visualizes clusters with t-SNE and Isomap to uncover patterns, assess manifold complexity, and evaluate classification challenges.

## Contents
- **Part A**: Data preprocessing, EDA, and target variable creation.
- **Part B**: t-SNE implementation with varying perplexities for local cluster visualization and veracity inspection.
- **Part C**: Isomap for global structure analysis and comparison with t-SNE.

## Requirements
- Python 3.x
- Libraries: pandas, numpy, matplotlib, scikit-learn

## Usage
1. Place `yeast.csv` in the project directory.
2. Open `Assignment_5.ipynb` in Jupyter and run cells sequentially.
3. Adjust parameters like perplexity for t-SNE or n_neighbors for Isomap.

## Key Insights
- t-SNE (perplexity=45) balances local/global structures; identifies noisy labels and outliers.
- Isomap preserves global geometry better than t-SNE.
- Reveals moderately curved data manifold, suggesting nonlinear methods for classification.

For details, refer to notebook visualizations.
