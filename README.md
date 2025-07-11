# Shortlisted_Compounds_Lipinski-s_Rule_of_Five
This repository contains Python code and a Jupyter Notebook for evaluating shortlisted compounds
based on Lipinski’s Rule of Five, a key guideline for assessing the drug-likeness of small molecules.

Contents
--------
- Shortlisted_compound_project.ipynb — Jupyter Notebook with:
  - Data of shortlisted compounds
  - Calculation of Lipinski’s Rule of Five parameters
  - Analysis & filtering based on these rules
  - Visualization and summary of results
- README.md — Project overview and instructions
- (Optional) requirements.txt — Python dependencies

Features
--------
- Input swissadme_s.csv data.
- Calculate key molecular descriptors:
  - Molecular weight (MW)
  - LogP (octanol-water partition coefficient)
  - Hydrogen bond donors (HBD)
  - Hydrogen bond acceptors (HBA)
- Evaluate compounds against Lipinski’s criteria:
  - MW ≤ 500 Da
  - LogP ≤ 5
  - HBD ≤ 5
  - HBA ≤ 10
- Identify compounds that pass or fail.
- Visualize the distribution of properties.
- Export or display shortlisted candidates.
- Output short_listed.csv data
Getting Started
---------------

1. Clone the repository
   git clone https://github.com/Niaz4020/Shortlisted_Compounds_Lipinski-s_Rule_of_Five.git
   

2. Install required libraries
   python -m venv venv
   source venv/bin/activate  # Windows: venv\Scripts\activate
   pip install -r requirements.txt

   If you don’t have requirements.txt, install manually:
   pip install pandas numpy rdkit matplotlib seaborn jupyterlab

3. Launch the notebook
   jupyter notebook

   Open Shortlisted_compound_project.ipynb and run the cells step by step.

Requirements
------------

- Python >= 3.8
- Jupyter Notebook
- pandas, numpy, rdkit, matplotlib, seaborn

Author
------
S M Riaduzzaman Niaz

License
-------

This project is open-source. Please cite the author if you reuse or adapt this work.
