#  Repository for Learning "DATA"

A personal learning repository for Data Analysis and Data Science using Python and Google Collab. This repo serves as my structured notebook collection from foundations all the way to machine learning and projects.


**Tools & Technologies:**

- Python 3
- Google Colab
- Pandas, NumPy
- Matplotlib, Seaborn, Plotly
- Scikit-learn
- SQL (basics)


###  Repository Structure

```
data-analysis-practice/
│
├── 00-Data Visualization
├── 01-foundations/
├── 02-wrangling/
├── 03-eda/
├── 04-analysis-ml/
├── 05-data-science/
├── 06-Data-Roles
├── 07-ProjectsorDatasets
├── 08 Attachements (Just images)
└── resources/
```



#####  Learning Path

### Phase 1  Foundations

> Folder: `/01-foundations/`

Building the core Python and data handling skills needed before everything else.

|Notebook|Topics Covered|
|---|---|
|`01_python_refresher.ipynb`|Data types, loops, functions, OOP basics|
|`02_numpy_basics.ipynb`|Arrays, operations, broadcasting|
|`03_pandas_intro.ipynb`|Series, DataFrames, indexing, slicing|

### Phase 2  Data Wrangling

> Folder: `/02-wrangling/`

Learning how to clean and prepare messy real-world data.

|Notebook|Topics Covered|
|---|---|
|`01_handling_nulls.ipynb`|Missing values, imputation strategies|
|`02_duplicates_outliers.ipynb`|Detecting and handling bad data|
|`03_merging_dataframes.ipynb`|Joins, merges, concatenation|
|`04_groupby_aggregation.ipynb`|Grouping, pivot tables, aggregation|


### Phase 3  Exploratory Data Analysis (EDA)

> Folder: `/03-eda/`

Understanding data through statistics and visualization.

|Notebook|Topics Covered|
|---|---|
|`01_descriptive_stats.ipynb`|Mean, median, mode, variance, distributions|
|`02_matplotlib_basics.ipynb`|Line charts, bar charts, histograms|
|`03_seaborn_visualizations.ipynb`|Heatmaps, boxplots, pairplots|
|`04_correlation_analysis.ipynb`|Correlation matrix, feature relationships|



### Phase 4 Analysis and Intro to ML

> Folder: `/04-analysis-ml/`

From statistical analysis to basic machine learning.

|Notebook|Topics Covered|
|---|---|
|`01_hypothesis_testing.ipynb`|t-tests, p-values, statistical significance|
|`02_ab_testing.ipynb`|A/B testing setup and interpretation|
|`03_linear_regression.ipynb`|Simple and multiple linear regression|
|`04_classification_basics.ipynb`|Logistic regression, KNN, Decision Trees|
|`05_model_evaluation.ipynb`|Accuracy, precision, recall, F1, confusion matrix|

### Phase 5  Data Science

> Folder: `/05-data-science/`

Going deeper into machine learning and data science concepts.

|Notebook|Topics Covered|
|---|---|
|`01_intro_to_ml.ipynb`|ML pipeline, train/test split, overfitting|
|`02_supervised_learning.ipynb`|Random Forest, SVM, XGBoost|
|`03_unsupervised_learning.ipynb`|K-Means clustering, PCA|
|`04_feature_engineering.ipynb`|Encoding, scaling, feature selection|
|`05_model_tuning.ipynb`|GridSearchCV, cross-validation|
|`06_deep_learning_intro.ipynb`|Neural networks basics with TensorFlow/Keras|


### Phase 6  Projects

> Folder: `/06-projects/`

End-to-end projects using real-world datasets.

|Project|Description|Dataset Source|
|---|---|---|
|`project-01-health/`|Analyzing health indicators and disease trends|Kaggle / WHO|
|`project-02-finance/`|Stock data analysis and trend exploration|Yahoo Finance API|
|`project-03-ph-data/`|Philippine socioeconomic or public dataset analysis|PSA / data.gov.ph|

Each project folder contains:

```
project-XX/
├── notebook.ipynb   ← main analysis
├── dataset.csv      ← raw data
└── README.md        ← project summary and findings
```


## 🔧 How to Use This Repo

1. Open any `.ipynb` file
2. Click **"Open in Colab"** badge (or upload manually to [colab.research.google.com](https://colab.research.google.com/))
3. Mount Google Drive if you need to save outputs:

```python
from google.colab import drive
drive.mount('/content/drive')
```

4. Run cells top to bottom and follow along with the notes



-----

Repository Created : 24-06-26
Status : Incomplete/Updating..