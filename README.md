Decision Tree Analysis on Census Data

The notebook includes the following steps:

1. **Data Quality Analysis and Pre-Processing:**
   - Loading the dataset from a URL.
   - Checking the shape and data types of the dataframe.
   - Identifying missing values.
   - Visualizing the distribution of each categorical feature.
   - Creating a data quality report.

2. **Decision Tree Classifier Model:**
   - Splitting the data into training and test sets.
   - Encoding categorical variables.
   - Fitting a decision tree model.
   - Visualizing the decision tree.

3. **Decision Tree Model Evaluation:**
   - Generating a classification report.
   - Displaying a confusion matrix.

4. **Tuning Decision Tree Performance:**
   - Training and testing the model with different hyperparameters.
   - Plotting accuracy graphs for different hyperparameters.

5. **Model Run Time Calculation:**
   - Calculating the run time of the model fitting process.

6. **Prediction and Probability Scoring:**
   - Making predictions with the trained model.
   - Calculating the probability score for the predicted class.

Key Libraries Used

- `pandas` for data manipulation.
- `matplotlib` and `seaborn` for data visualization.
- `sklearn` for machine learning model training, evaluation, and encoding.

How to Run

To run this notebook:

1. Install the required libraries:
   ```
   pip install numpy pandas matplotlib seaborn scikit-learn
   ```
2. Open the notebook in Jupyter Notebook or JupyterLab.
3. Run the cells in order.

Authors
Aaron Masek
Karen Palaha
Lauryn Carter
