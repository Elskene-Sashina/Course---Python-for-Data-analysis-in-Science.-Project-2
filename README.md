# 🔬 Make Matrix of Genetic Distances

This is the second project I completed as part of the course on Python for Data Analysis in Science. The task involved developing a **matrix of genetic distances** between genes. Use the **Levenshtein distance** and visualize the result as a **hitmap**.

---

## 📋 **Table of Contents**
- [Project Description]
- [Technologies Used]
- [Installation]
- [Usage]
- [Example Data]
- [MOST Important Note]

---

## 📝 **Project Description**

This project focuses on the following tasks:
1. **Reading input data** from a file (e.g., CSV, Excel).
2. **Data cleaning and preprocessing**.
3. **Statistical analysis** (e.g., calculating descriptive statistics).
4. **Data visualization** using plots, charts, and graphs.
5. **Saving analysis results** to output files (e.g., CSV, images).

---

## 🔧 **Technologies Used**

The project is implemented in **Python** and uses the following libraries:
- **pandas** — for data manipulation and analysis.
- **numpy** — for mathematical operations.
- **matplotlib** and **seaborn** — for data visualization.
- **scipy** — for advanced statistical analysis.
- **biopython** — for biologycal analysis.

---

## 🚀 **Installation**

1. Clone the repository from GitHub:
   git clone **https://github.com/Elskene-Sashina/Course---Python-for-Data-analysis-in-Science.-Project-2.git**

2. Install and import modules:

**pip install pandas numpy matplotlib seaborn scipy**

**pip install python-Levenshtein**

**pip insall biopython**





**from Levenshtein import distance as lev**

**from Bio import SeqIO**

**fimport numpy as np**

**fimport matplotlib.pyplot as plt**

**fimport seaborn as sns**

---

## ⚙️ **Usage**

1.Place your input data file (e.g., CSV, Excel) in the project directory.

2.Update the script to specify your input file's name and path:
**resulting_function(' 
                   #PUT HERE YOUR FASTA FILE
                   ')**

3.The result will be saved to the output directory specified in the code.

---

## 📊 **Example Data**

Input File ('YOUR_NAME_FILE.csv'):

| ID  | Sample Name | Measurement 1 | Measurement 2 |
|-----|-------------|----------------|----------------|
| 1   | Sample_A    | 12.5           | 34.2           |
| 2   | Sample_B    | 10.1           | 29.5           |
| 3   | Sample_C    | 11.3           | 33.8           |
---

## 🔍 **MOST Important Note**

At the end of the code, you will see the following section:

**#TRY**
**resulting_function(' 
                   #PUT HERE YOUR FASTA FILE
                   ')**

Here, you must specify the name of your input FASTA file.

Good luck! 🍀
