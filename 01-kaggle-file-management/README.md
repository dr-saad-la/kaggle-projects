# Working with Directories and Files in Kaggle

## Project Information
- **Author**: Dr. Saad Laouadi
- **Date**: April 19, 2025
- **Dataset**: Heart Failure Synthetic Dataset
- **Version**: 1.0

## Overview
This notebook demonstrates efficient techniques for file and directory management within the Kaggle environment. Understanding how to properly navigate and manipulate the file system is essential for productive data science workflows, especially when working with complex datasets.

## Key Features
- Exploration of Kaggle's file system structure
- Implementation of robust file handling using pathlib
- Creation of reproducible data loading patterns
- Demonstration of best practices for organizing data science projects

## Dataset Information

This project uses the Heart Failure Synthetic Dataset available on Kaggle. The dataset contains simulated medical records focused on heart failure conditions.

### Dataset Download Instructions

To download this dataset for local use:

```bash
# List details about the dataset
kaggle datasets list -s "heart failure prediction"

# Download the complete dataset
kaggle datasets download fedesoriano/heart-failure-prediction

# OR download just the specific CSV file
kaggle datasets download -f heart_failure_clinical_records_dataset.csv fedesoriano/heart-failure-prediction
```

## Files in this Directory

- `working-with-files-kaggle.ipynb`: Main Jupyter notebook containing the analysis
- `README.md`: This file with project information
- `requirements.txt`: Python dependencies needed to run the notebook

## Usage

1. Ensure you have set up the Kaggle API (see main repository README)
2. Download the dataset using the commands above
3. Run the notebook in Jupyter:
   ```bash
   jupyter notebook working-with-files-kaggle.ipynb
   ```

## Skills Demonstrated

- **Path Management**: Using modern `pathlib` for cross-platform compatibility
- **Error Handling**: Implementing robust error checking for file operations
- **Workflow Optimization**: Techniques for efficient data loading and processing
- **Project Organization**: Best practices for structuring machine learning projects

## Kaggle Link

View this notebook on Kaggle: [Working with Directories and Files in Kaggle](https://www.kaggle.com/code/saadlaouadi/working-with-directories-and-files-in-kaggle)

## Dependencies

- Python 3.9+
- pandas
- numpy
- matplotlib
- seaborn
- pathlib
- watermark

Install dependencies using:

```bash
pip install -r requirements.txt
```

## References

- [Kaggle Notebooks Documentation](https://www.kaggle.com/docs/notebooks)
- [Python Pathlib Documentation](https://docs.python.org/3/library/pathlib.html)
- [Best Practices for File Handling in Python](https://realpython.com/working-with-files-in-python/)
