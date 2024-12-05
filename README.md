# README

## Spezifikation und Implementierung eines Pre-Consent Mechanismus im Kontext der Digitalisierung von Hochschulausweisen als Verifiable Credentials auf Basis von ISO/IEC 18013-5 

> **English Title:** 
> Specification and implementation of a pre-consent mechanism in the context of the digitization of university ID cards as verifiable credentials based on ISO/IEC 18013-5

## 🎯 Project Overview 

This project is part of my **master’s thesis**, focusing on the evaluation of a user study. 
The study examines the impact of the pre-consent mechanism in a wallet-app, comparing two variants: **With Pre-Consent** and **Without Pre-Consent**. 
The data required for analysis is stored in the `data` folder, which includes:

- 📊 User responses
- ⏱️ Timestamp files for each participant

## 📂 Project Structure 

The analysis is divided into two Jupyter notebooks:

1. 📋 **Questionnaire Notebook**   
   Analyzes participants' responses to the questionnaire provided after using both variants of the wallet-app. Focuses on user perceptions, including usability, acceptance, and specific questions related to verifiers and transactions.

2. ⏱️ **Efficiency Notebook**   
   Analyzes the timestamps logged during each consent process (start and end time). Evaluates the efficiency of the pre-consent mechanism in terms of task duration.

## 🛠️ Prerequisites 

To run the analysis, you need:
- **Python** installed on your system 🐍
- **Jupyter Notebook** installed. You can install it via pip:

```bash
pip install jupyter
```

For more details, visit: [Jupyter Installation Guide](https://jupyter.org/install)

## 🚀 How to Run

1. Clone the repository
2. Open the Jupyter Notebook in your terminal:

```bash
jupyter notebook
```

3. Open the notebook you wish to analyze (`Questionnaire.ipynb` or `Efficiency.ipynb`) from the Jupyter interface in your browser.
4. Run the cells to see the results.

## 📦 Package Installation 
All required Python packages are installed in the first cell of each notebook. Ensure you run the first cell before proceeding with the analysis.