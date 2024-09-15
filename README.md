# Breast Cancer Diagnosis Prediction

## Description

This project aims to predict breast cancer diagnosis based on various features of cell nuclei, such as radius, texture, and smoothness. The dataset includes multiple attributes related to cell measurements, and the analysis involves data preprocessing, feature engineering, model training, and evaluation using various classifiers.

## Data

The dataset consists of the following columns:
- `id`: Patient ID
- `diagnosis`: Diagnosis (M = malignant, B = benign)
- `radius_mean`: Mean radius
- `texture_mean`: Mean texture
- `perimeter_mean`: Mean perimeter
- `area_mean`: Mean area
- `smoothness_mean`: Mean smoothness
- `compactness_mean`: Mean compactness
- `concavity_mean`: Mean concavity
- `concave points_mean`: Mean concave points
- `symmetry_mean`: Mean symmetry
- `fractal_dimension_mean`: Mean fractal dimension
- `radius_se`: Radius SE
- `texture_se`: Texture SE
- `perimeter_se`: Perimeter SE
- `area_se`: Area SE
- `smoothness_se`: Smoothness SE
- `compactness_se`: Compactness SE
- `concavity_se`: Concavity SE
- `concave points_se`: Concave points SE
- `symmetry_se`: Symmetry SE
- `fractal_dimension_se`: Fractal dimension SE
- `radius_worst`: Worst radius
- `texture_worst`: Worst texture
- `perimeter_worst`: Worst perimeter
- `area_worst`: Worst area
- `smoothness_worst`: Worst smoothness
- `compactness_worst`: Worst compactness
- `concavity_worst`: Worst concavity
- `concave points_worst`: Worst concave points
- `symmetry_worst`: Worst symmetry
- `fractal_dimension_worst`: Worst fractal dimension

## Usage

To use this project, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/Breast_Cancer_Diagnosis_Prediction.git
```
### 2. Navigate to the Project Directory

```bash
cd Breast_Cancer_Diagnosis_Prediction
```
### 3. Install Dependencies

Ensure you have the required Python packages installed:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```
### 4. Run the Jupyter Notebook

Launch Jupyter Notebook and open `notebooks/Breast_Cancer.ipynb`:

```bash
jupyter notebook
```
