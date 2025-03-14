# Machine Learning-based: Enhanced Categorization of Cybersecurity Vulnerabilities

[![GitHub license](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/your-username/your-repo-name/blob/main/LICENSE)  
[![Paper](https://img.shields.io/badge/Paper-PDF-red.svg)](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10754709)  
[![Poster](https://img.shields.io/badge/Poster-PDF-orange.svg)](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=fk1n8VQAAAAJ&citation_for_view=fk1n8VQAAAAJ:qjMakFHDy7sC)

This repository contains the code, datasets, and results of our research on **Machine Learning-based categorization of cybersecurity vulnerabilities in software**, published at **2024 IEEE UEMCON**. The project was also awarded **Best Research Poster** at Tennessee Tech’s Annual Research Conference.

## Table of Contents
- [Overview](#overview)
- [Research Paper & Poster](#research-paper--poster)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contact](#contact)

## Overview
Software vulnerabilities pose security risks, and traditional classification methods can be slow and error-prone. This project utilizes **Machine Learning** to automate and improve the categorization of cybersecurity vulnerabilities.

## Research Paper & Poster
- **Paper:** [IEEE UEMCON 2024](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10754709)  
- **Poster:** [Tennessee Tech Research Conference](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=fk1n8VQAAAAJ&citation_for_view=fk1n8VQAAAAJ:qjMakFHDy7sC)

## Installation
Follow these steps to set up the project:
```bash
# Clone the repository
git clone https://github.com/EkleTony/CyberVuln-ML.git

# Navigate to the project directory
cd ML-CVE-Categorization

# Install required dependencies
pip install -r requirements.txt
```

### Requirements
The following dependencies are required to run the project:
- Python 3.x
- Jupyter Notebook
- NumPy
- Pandas
- Scikit-learn
- TensorFlow
- Torch
- Matplotlib
- Seaborn
- NLTK
- TQDM
- WordNetLemmatizer (NLTK)
- IMBlearn (SMOTE)
- OS
- RE (Regular Expressions)
- String

Ensure the dataset is placed in the correct directory before running the notebooks.

## Usage
Run the Jupyter Notebook using:
```bash
jupyter notebook JupyterNote_CVE_Prediction_Code.ipynb
```

## License
This project is licensed under the **MIT License**. You are free to use, modify, and distribute the dataset and code with proper attribution. However, if using this dataset in academic or research work, please **cite the following paper**:

```
@inproceedings{ekle2024enhanced,
  title={Enhanced Categorization of Cybersecurity Vulnerabilities},
  author={Ekle, Ocheme Anthony and Ulybyshev, Denis},
  booktitle={2024 IEEE 15th Annual Ubiquitous Computing, Electronics \& Mobile Communication Conference (UEMCON)},
  pages={800--806},
  year={2024},
  organization={IEEE}
}
```

