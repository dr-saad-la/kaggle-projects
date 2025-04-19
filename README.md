# Data Science Portfolio: Kaggle Projects

![Data Science Banner](https://img.shields.io/badge/Data%20Science-Portfolio-blue)
![Python](https://img.shields.io/badge/Python-3.9%2B-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow)

A collection of data science projects, analyses, and experiments conducted on the Kaggle platform by Dr. Saad Laouadi.

## 📂 Repository Structure

```
kaggle-projects/
├── notebooks/
│   ├── file-management/          # Working with directories and files in Kaggle
│   └── [future-projects]/        # Additional project directories
├── common/                       # Shared utility functions
│   └── file_utils.py
└── README.md                     # This file
```

## 🚀 Projects

### [Working with Files and Directories in Kaggle](./notebooks/file-management/)

An in-depth exploration of file system management in Kaggle environments, demonstrating best practices for organizing, accessing, and manipulating files and directories for data science projects.

**Skills demonstrated:**
- Robust path handling with `pathlib`
- Error-resistant file operations
- Dataset organization techniques
- Reproducible data loading patterns

**[View on Kaggle →](https://www.kaggle.com/yourusername/working-with-directories-and-files-in-kaggle)**

### [Future Project Name]

*Coming soon*

## 📊 Dataset Access Instructions

### Heart Failure Synthetic Dataset

To download the Heart Failure Synthetic Dataset used in these notebooks, you can use the Kaggle API:

#### Prerequisites
1. Install the Kaggle API:
   ```bash
   pip install kaggle
   ```

2. Set up your Kaggle API credentials:
   - Go to your [Kaggle account settings](https://www.kaggle.com/account)
   - Scroll to the API section and click "Create New API Token"
   - Save the downloaded `kaggle.json` file to `~/.kaggle/kaggle.json` (Linux/macOS) or `C:\Users\<Windows-username>\.kaggle\kaggle.json` (Windows)
   - Set permissions: `chmod 600 ~/.kaggle/kaggle.json` (Linux/macOS only)

#### Download Commands

Download the dataset using:
```bash
# List related datasets
kaggle datasets list -s "heart failure"

# Download the specific dataset
kaggle datasets download fedesoriano/heart-failure-prediction

# OR download just the specific file
kaggle datasets download -f heart_failure_clinical_records_dataset.csv fedesoriano/heart-failure-prediction
```

For more information on using the Kaggle API, see [Kaggle's API documentation](https://github.com/Kaggle/kaggle-api).

## 🛠️ Setup and Usage

To use these notebooks locally:

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/kaggle-projects.git
   cd kaggle-projects
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Download datasets using the instructions above

5. Open the notebooks in Jupyter:
   ```bash
   jupyter notebook
   ```

## 📚 Resources

- [Kaggle Documentation](https://www.kaggle.com/docs)
- [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)
- [Effective Python for Data Science](https://www.effectivepython.com/)

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📧 Contact

- Dr. Saad Laouadi
- [LinkedIn](https://www.linkedin.com/in/yourusername/)
- [Kaggle Profile](https://www.kaggle.com/yourusername)

---

⭐ **If you find these projects useful, please consider giving this repository a star!** ⭐