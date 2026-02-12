# End-to-End-Machine-Learning-Pipeline

📂 Dataset

File: Titanic-Dataset.csv

Target Variable: Survived (0 = No, 1 = Yes)

🎯 Objective

To build a complete Machine Learning pipeline that preprocesses data and predicts passenger survival using Logistic Regression.

🛠️ Steps Performed

Loaded dataset and separated features (X) and target (y).

Identified numerical and categorical features.

Applied preprocessing using ColumnTransformer:

StandardScaler for numerical features

OneHotEncoder for categorical features

Created a full Pipeline combining preprocessing and model.

Split data into train and test sets.

Trained the pipeline and generated predictions.

Evaluated performance using:

Accuracy

Precision

Recall

F1-score

📊 Evaluation metrics

Accuracy: 0.804

Precision: 0.793

Recall: 0.667

F1-score: 0.724

📦 Deliverables

Jupyter Notebook: Titanic_ML_Pipeline.ipynb

Saved pipeline model: titanic_pipeline_model.pkl

✅ Conclusion

The ML pipeline successfully integrates preprocessing and model training into a single reusable workflow, making it efficient for deployment and future predictions.
