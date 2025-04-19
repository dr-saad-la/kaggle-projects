# Data Science Portfolio: Kaggle Projects

![Data Science Banner](https://img.shields.io/badge/Data%20Science-Portfolio-blue)
![Python](https://img.shields.io/badge/Python-3.9%2B-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow)

A collection of data science projects, analyses, and experiments conducted on the Kaggle platform by **Dr. Saad Laouadi.**

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

### [Working with Files and Directories in Kaggle](./notebooks/01-kaggle-file-management/)



An in-depth exploration of file system management in Kaggle environments, demonstrating best practices for organizing, accessing, and manipulating files and directories for data science projects.

**Skills demonstrated:**
- Robust path handling with `pathlib`
- Error-resistant file operations
- Dataset organization techniques
- Reproducible data loading patterns

**[View on Kaggle →](https://www.kaggle.com/code/saadlaouadi/working-with-directories-and-files-in-kaggle)**

### Heart Failure Analysis

*Coming soon*

## 🔍 Kaggle API Setup

To access datasets used in these projects locally, you'll need to set up the Kaggle API:

### Prerequisites
1. Install the Kaggle API:
   ```bash
   pip install kaggle
   ```

2. Set up your Kaggle API credentials:
   - Go to your [Kaggle account settings](https://www.kaggle.com/account)
   - Scroll to the API section and click "Create New API Token"
   - Save the downloaded `kaggle.json` file to:
     - Linux/macOS: `~/.kaggle/kaggle.json`
     - Windows: `C:\Users\<Windows-username>\.kaggle\kaggle.json`
   - Set proper permissions (Linux/macOS only):
     ```bash
     chmod 600 ~/.kaggle/kaggle.json
     ```

3. See each project's README for specific dataset download instructions.

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

4. Download datasets using project-specific instructions

5. Open the notebooks in Jupyter:
   ```bash
   jupyter notebook
   ```

## 📚 Resources

- [Kaggle Documentation](https://www.kaggle.com/docs)
- [Kaggle API GitHub Repository](https://github.com/Kaggle/kaggle-api)
- [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)
- [Effective Python for Data Science](https://www.effectivepython.com/)

## 📝 License

This project is licensed under the Apache 2.0 License - see the [LICENSE](LICENSE) file for details.

## 📧 Contact

- Dr. Saad Laouadi
- [LinkedIn](https://www.linkedin.com/in/saad-laouadi/)
- [Kaggle Profile](https://www.kaggle.com/saadlaouadi)

---

⭐ **If you find these projects useful, please consider giving this repository a star!** ⭐

