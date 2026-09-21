<div align="center">

# Machine Learning Notebooks

_Jupyter notebooks from UCAB's INFO-02020 course on Artificial Intelligence and Machine Learning_

[![Language](https://img.shields.io/badge/Language-Python%203-3776ab?labelColor=181825&style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Tool](https://img.shields.io/badge/Tool-Jupyter-f37626?labelColor=181825&style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Runtime](https://img.shields.io/badge/Runtime-Google%20Colab-f9ab00?labelColor=181825&style=for-the-badge&logo=googlecolab&logoColor=white)](https://colab.research.google.com/)
[![License](https://img.shields.io/github/license/Badjavii/machine-learning-notebook?color=a6e3a1&labelColor=181825&style=for-the-badge)](https://github.com/Badjavii/machine-learning-notebook/blob/main/LICENSE)

[Leer este README en español](./es/README.md)

</div>

## About this repository

This repository is my personal working copy of the Jupyter notebooks used in **INFO-02020: Artificial Intelligence, Machine Learning**, taught at UCAB's School of Software Engineering by **Prof. Didi Ramsaran Chin**.

Every notebook is preserved in its original English form and mirrored in a Spanish translation. The translations keep variable names, function names and dataset column names intact so the code runs identically in both versions. Only prose, comments, docstrings, print statements and assertion messages are localised. Outputs are kept in the committed notebooks so the material is fully readable directly from GitHub without needing to execute anything.

The material covers the standard path from Python fundamentals for data science, through NumPy and Pandas, into visualization with Matplotlib and Seaborn, and finally into Scikit-Learn's classical machine learning workflow. Hands-on `# YOUR TURN` exercises are embedded throughout.

## Notebooks

Notebooks are grouped by week (`W`) and day (`D`). New material is added throughout the semester.

| Week | Topic | English | Spanish |
|---|---|---|---|
| W1 · D2 | Foundations of Python for Data Science and ML | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Badjavii/machine-learning-notebook/blob/main/en/W1_D2_intro_python.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Badjavii/machine-learning-notebook/blob/main/es/W1_D2_intro_python.ipynb) |

## Repository structure

```
machine-learning-notebook/
├── README.md            English README (this file)
├── LICENSE              MIT license
├── .gitignore
├── en/                  Original notebooks in English
│   └── W1_D2_intro_python.ipynb
└── es/                  Spanish translations
    ├── README.md
    └── W1_D2_intro_python.ipynb
```

## How to use

### Option 1: Google Colab (recommended)

Click any **Open In Colab** badge in the [Notebooks](#notebooks) table. The notebook opens in Colab with the standard data science stack preinstalled and a free GPU or TPU available on demand. Sign in with a Google account and choose *File > Save a copy in Drive* to edit your own version.

### Option 2: Local Jupyter with Anaconda (recommended for local runtime)

[Anaconda](https://www.anaconda.com/download) ships with Python, Jupyter, NumPy, Pandas, Matplotlib, Seaborn and Scikit-Learn preinstalled, so once it is installed there is nothing else to set up.

```bash
git clone https://github.com/Badjavii/machine-learning-notebook.git
cd machine-learning-notebook

# Launch Jupyter (Anaconda already includes it)
jupyter notebook
```

Alternatively you can open Anaconda Navigator and launch Jupyter from the graphical interface, then navigate to the cloned folder.

### Option 3: Local Jupyter with plain Python

If you prefer a lightweight setup without Anaconda:

```bash
git clone https://github.com/Badjavii/machine-learning-notebook.git
cd machine-learning-notebook

# Create and activate a virtual environment
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate

# Install the standard data science stack
pip install numpy pandas matplotlib seaborn scikit-learn jupyter

# Launch Jupyter
jupyter notebook
```

Then open any `.ipynb` file from the `en/` or `es/` folder.

## Disclaimer and credits

The original notebook content, including exercises, explanations, structure and pedagogical design, was authored by **Prof. Didi Ramsaran Chin** for UCAB's INFO-02020 course. This repository exists solely for personal study purposes and to make the material accessible in Spanish for classmates who may benefit from a translated version.

All intellectual credit for the course material belongs to Prof. Ramsaran Chin and UCAB. The MIT license in this repository covers only my Spanish translations and any personal additions or exercise solutions I contribute.

**UCAB · Universidad Católica Andrés Bello · Faculty of Engineering**
_School of Software Engineering · INFO-02020 · Section 202715_

## Credits

This repository is maintained by **Badjavii**, junior developer.