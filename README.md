# Machine Learning Approach to Diagnose Lung Cancer

This project presents a machine learning-based approach for the early diagnosis of lung cancer, integrating Explainable Artificial Intelligence (XAI) and Active Learning techniques to improve model interpretability and diagnostic precision.

## Academic Information
- 📘 Course: Artificial Intelligence — Academic Year 2025/2026
- 🧬 Degree: Master in Computational Biology | University of Coimbra

## Authors
- Guilherme Cardoso — nº 2021226995
- Julieta Carmo — nº 2021228206
- Maria Inês Gomes — nº 2021222220

## Getting Started

### Prerequisites
This project was developed on Google Colab, which provides an online environment with all necessary Python libraries installed. You only need a Google account to run the notebook.

### Installation
1. Clone this repository or download the notebook file `.ipynb`.
2. Open the notebook using Google Colab at [colab.research.google.com](https://colab.research.google.com/).
3. Upload the dataset file `survey lung cancer.csv` to the Colab environment using the upload button or mount your Google Drive.
4. Ensure all required libraries are installed by running the first notebook cells. For example, the `lime` package is installed using:

`!pip install lime`

## Usage
- Run the notebook cells sequentially to execute the data loading, preprocessing, model training, and evaluation steps as outlined.
- The notebook prints dataset overview and checks for duplicates and missing values.
- Various classifiers and explainability techniques such as SHAP are used for diagnosis analysis.

## Dataset
The dataset used is `survey lung cancer.csv`. Ensure this file is uploaded in the same directory as the notebook on Google Colab.
