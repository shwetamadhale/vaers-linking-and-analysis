# Symptom Extraction and Linking from VAERS (NLP, Prompting)

A Python-based project that extracts symptoms from VAERS reports using natural language processing (NLP) and machine learning techniques, with a focus on named entity recognition (NER) and entity linking.

## Table of Contents
- [Background](#background)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Background
This project processes data from the Vaccine Adverse Event Reporting System (VAERS) to extract and analyze symptoms related to vaccine reactions. It leverages NLP and machine learning to classify symptoms, perform entity linking, and generate insights from the reports.

## Features
- **Data Extraction**: Reads and processes VAERS reports.
- **Text Preprocessing**: Cleans and normalizes symptom descriptions.
- **Named Entity Recognition (NER)**: Identifies and extracts symptom-related entities.
- **Entity Linking**: Associates extracted symptoms with external medical databases.
- **Machine Learning Models**: Implements supervised and unsupervised learning for text classification and clustering.
- **Visualization**: Provides statistical insights using graphical representations.

## Technologies Used
- **Python**: Core programming language.
- **Natural Language Processing (NLP)**:
  - SpaCy, NLTK, and Transformers for text processing and NER.
- **Machine Learning**:
  - Scikit-learn for classification and clustering.
- **Data Handling**:
  - Pandas and NumPy for data manipulation.
- **Database & Storage**:
  - SQL for structured data storage.
- **Visualization**:
  - Matplotlib and Seaborn for graphical representation.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/shwetamadhale/SymptomExtractionVAERS.git
   ```
2. Navigate to the project directory:
   ```sh
   cd SymptomExtractionVAERS
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Run the symptom extraction script:
   ```sh
   python extract_symptoms.py
   ```
5. Run the analysis and entity linking:
   ```sh
   python analyze_vaers.py
   ```

## Usage
1. **Extract Symptoms from VAERS Reports**:
   - Load the VAERS dataset (CSV format).
   - Perform NLP preprocessing on symptom descriptions.
2. **Perform Named Entity Recognition (NER) & Entity Linking**:
   - Use pre-trained models to detect symptoms.
   - Link symptoms to external medical knowledge bases.
3. **Apply Machine Learning Models**:
   - Train classifiers for symptom categorization.
   - Perform clustering to discover symptom patterns.
4. **Visualize Findings**:
   - Generate plots for symptom frequency, severity distribution, and patient demographics.

## Project Structure
```
SymptomExtractionVAERS/
│── analyze_vaers.py       # Script for entity linking & analysis
│── extract_symptoms.py    # Extracts symptoms from VAERS reports
│── requirements.txt       # List of dependencies
│── covid_file.csv         # Raw VAERS dataset
│── extracted_symptoms.txt # Processed symptom data
│── notebooks/             # Jupyter notebooks for analysis
```


