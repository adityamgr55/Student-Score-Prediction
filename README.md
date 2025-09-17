# Student Score Prediction

This project predicts student performance based on various academic and demographic factors using machine learning models. The workflow includes data preprocessing, visualization, handling missing values, encoding categorical variables, dealing with outliers, and model building.

## Project Workflow

1. **Importing Libraries**
   - Essential Python libraries for data manipulation, visualization, and machine learning.

2. **Data Cleaning & Preprocessing**
   - Handling missing values (dropping rows with minimal nulls).
   - Splitting columns for better feature representation.
   - Encoding categorical columns into numerical format.
   - Outlier detection and removal.

3. **Exploratory Data Analysis (EDA)**
   - Visualizing distributions and relationships between features and target variables.
   - Identifying key factors influencing student scores.

4. **Modeling**
   - Building and comparing multiple machine learning models.
   - Training models on both datasets: with outliers and without outliers.
   - Evaluating performance using appropriate metrics.

## Technologies Used
- Python 3
- Pandas, NumPy (data manipulation)
- Matplotlib, Seaborn (visualization)
- Scikit-learn (machine learning models & preprocessing)

## How to Run
1. Clone the repository or download the notebook file.
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Final_studentscoreprediction.ipynb
   ```
4. Run all cells to reproduce results.

## Results
- The notebook compares models with and without outlier handling.
- It highlights how preprocessing impacts prediction accuracy.

## Future Improvements
- Hyperparameter tuning for better model performance.
- Trying advanced models like XGBoost or Neural Networks.
- Adding cross-validation for robust evaluation.


