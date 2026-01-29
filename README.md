# heart-disease-risk-prediction
Machine learning project predicting heart disease risk using Python and scikit-learn with multiple model comparisons.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

## Dataset
UCI Heart Disease (Cleveland) dataset containing patient health attributes such as age, cholesterol levels, resting blood pressure, and heart rate.

## Project Workflow
1. **Data Loading & Cleaning**
   - Handled missing and duplicate values
   - Converted categorical/object columns to numeric
   - Binarised the target variable (0 = no disease, 1 = disease present)

2. **Exploratory Data Analysis (EDA)**
   - Target distribution bar chart
   - Feature histograms
   - Correlation heatmap

3. **Preprocessing**
   - Train–test split
   - Feature scaling using StandardScaler

4. **Model Training**
   - Logistic Regression
   - Random Forest
   - Support Vector Machine (SVM)

5. **Evaluation Metrics**
   - Accuracy
   - Precision
   - Recall
   - ROC-AUC

6. **Model Comparison**
   - Visual comparison using bar charts

## Results
All models achieved strong and comparable performance, with Random Forest and SVM slightly outperforming Logistic Regression, indicating robust predictive patterns in the dataset.

## How to Run
1. Clone the repository  
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Open the notebook and run all cells
