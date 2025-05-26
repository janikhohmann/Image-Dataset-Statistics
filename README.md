# Image-Dataset-Statistics
This repository provides an easily customizable script for the initial analysis of image datasets, specifically for use in machine learning.


## Features
- Calculate and visualize brightness distributions across datasets
- Generate violin plots for dataset comparisons
- Perform statistical significance tests:
  - Mann-Whitney U test for comparing two datasets
  - Kruskal-Wallis test with post-hoc analysis for multiple datasets
- Support for both images and video files (common formats: jpg, png, mp4, avi)

## Installation
```bash
git clone https://github.com/janikhohmann/Image-Dataset-Statistics.git
cd Image-Dataset-Statistics
pip install -r requirements.txt
```

## Output
The tool generates:

- Violin plots showing brightness distributions
- Statistical test results including p-values
- CSV files with detailed statistics