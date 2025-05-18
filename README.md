# roof_type_classification

This repository contains a Python script to train a roof-type classifier using EfficientNet and Stratified K-Fold cross-validation.

## Prerequisites

- Python 3.7+  
- Git  
- A folder of labeled roof "images" and a CSV mapping filenames to labels (roof_type_labels.csv).

## Data Layout

- data/images/
- data/roof_type_labels.csv

## Path Configuration

This script auto‐detects your project root and data locations:

- `root_dir` is set to your current working directory (`os.getcwd()`).  
- `csv_file` → `os.path.join(root_dir, "roof_type_labels.csv")`.  
- `image_dir` → `os.path.join(root_dir, "images")`.

