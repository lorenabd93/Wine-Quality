Wine Quality Analysis
=====================

Project Title
-------------
Wine Quality Analysis: Exploring Factors Contributing to Good Wine

Project Goal
------------
This project aims to process and analyze a dataset of red wine physicochemical properties 
to understand what factors contribute to a wine's quality.

Description
-----------
This Jupyter Notebook performs an initial exploration and preprocessing of a red wine quality dataset. 
It involves loading the data, performing basic descriptive statistics, checking for missing values, 
and implementing custom functions for data splitting and normalization. 

The project begins to lay the groundwork for identifying key parameters influencing wine quality.

Features
--------
- Data Loading:
  Reads the `winequality-red.csv` dataset.

- Initial Data Overview:
  - Displays sample rows
  - Dataset dimensions (1599 rows, 12 columns)
  - Descriptive statistics for all features

- Data Cleaning:
  Checks for and confirms the absence of null or missing values.

- Column Renaming:
  Renames original columns to shorter, more manageable abbreviations 
  (e.g., 'fixed acidity' to 'FA').

- Custom Train-Test Split:
  Implements a manual function `train_test_split_manual()` to divide the dataset 
  into training and testing sets based on a specified percentage 
  (default 30% for testing).

- Custom Data Normalization:
  Develops a custom function `normalize()` to scale numerical features to a range 
  between 0 and 1 (Min-Max Normalization), including handling edge cases where 
  minimum and maximum values are identical.

Key Observations
----------------
- The dataset contains 12 physicochemical parameters including fixed acidity, 
  volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, 
  total sulfur dioxide, density, pH, sulfates, alcohol, and quality.

- The highest wine quality observed in the dataset is 8.

- For wines with the highest quality (score 8), citric acid and density values 
  tend to be close to 1 (after normalization).

- Quality distribution:
  - 81.8% of samples have an average quality
  - 13.5% have a high quality
  - 4.6% have a low quality

Technologies Used
-----------------
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn (conceptual reference only; custom code was used for splitting)

How to Run
----------
1. Ensure you have Python installed, along with Jupyter Notebook and the libraries listed above.
2. Download the `Wine_lorena_project.ipynb` file and the `winequality-red.csv` dataset.
3. Place both files in the same directory.
4. Open a terminal or command prompt and navigate to the directory.
5. Run `jupyter notebook`.
6. Your web browser will open, displaying the Jupyter interface. 
   Click on `Wine_lorena_project.ipynb` to open and run the notebook cells.

Contact
-------
Feel free to connect with me on LinkedIn: 
https://www.linkedin.com/in/jeimi-lorena-barreto-degadillo/

