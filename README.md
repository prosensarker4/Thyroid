# Paper Title: Catboost with Physics-based Metaheuristics for Thyroid Cancer Recurrence Prediction

Steps:
1. Download the dataset (Thyroid_Diff.csv)
2. Download the Thyroid Cancer Recurrence Shared Code.ipynb file
3. Load the IPython notebook file to the Google Colab or Jupyter notebook.
4. Place the dataset path: # Load dataset data = pd.read_csv('dataset path')
5. Run the cells one by one.
6. You will notice the result given below:
   
## 📊 Only CatBoost

| Model    | Train Accuracy | Train F-score | Train Precision | Train Recall | Test Accuracy | Test F-score | Test Precision | Test Recall |
|----------|----------------|---------------|-----------------|--------------|---------------|--------------|----------------|-------------|
| CatBoost | **99.70**      | 99.48         | 100.00          | 98.96        | **95.83**     | 92.42        | 96.29          | 89.27       |

---

## ⚡ Optimized Classifiers

| Model | Train Accuracy | Train F1 Score | Train Precision | Train Recall | Test Accuracy | Test F1 Score | Test Precision | Test Recall |
|-------|----------------|----------------|-----------------|--------------|---------------|---------------|----------------|-------------|
| EVO   | 96.64          | 93.82          | 97.44           | 90.47        | 96.35         | 93.34         | 96.19          | 90.94       |
| EO    | 97.01          | 94.65          | 96.00           | 93.39        | 96.17         | 93.12         | 94.31          | 92.21       |
| EFO   | **97.61**      | **95.63**      | **97.78**       | **93.59**    | 96.17         | 93.09         | **95.78**      | 91.15       |


------------------------------------------------------------------------------------------------------------------------------------------------------------
The GitHub repository contains the data preparation, fold generation, and final model configuration codes. As the optimization code requires considerable computational time, it has not been included in the repository. However, the optimization code is available from the corresponding author upon reasonable request.
