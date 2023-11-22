# Dimensional-Reduction-Heart-Attack
This study aims to analyze the Heart Attack dataset and will apply Dimensionality Reduction techniques using **R** eventually building a classification model to do the predictions.

# Study Objective:
* Analysis and exploring different methods for Dimensionality Reduction and choosing the optimal
technique.
* Applying data wrangling techniques to perform exploratory data analysis to find the insights
from the data and handle any discrepancies.
* Comparison on different Machine learning models and compare their accuracy metrics.
* Predicting heart failure on basis of different attributes like cholesterol, chest pain type, etc and
comparison with the true/actual values.

# Population and Sampling: 

* The dataset includes a sample of patients within the age group of 29 and 77 years. The data is segregated between males and females.
* The total population is 16742 records which for the model training and validation purposes will be split into an 80-20 ratio.
* The two very famous approaches of Simple Random and Stratified sampling techniques will be evaluated on the dataset.

# Dataset Source: 

The dataset is taken from the open-source website, named, Kaggle. Here is the [link](https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset?resource=download) for reference.

# Feature Information:
_Con = Continuous, Dis = Discrete, Cat = Categorical_

| Feature Name | Data Type |
| :-----------:| :--------:|
| Age          | Con       |
| Sex          | Cat       |
| cp           | Dis       |
| trtbps       | Con       |
| chol         | Con       | 
| fbs          | Cat       |
| restecg      | Cat       |
| thalachh     | Con       |
| exang        | Cat       |
| ca           | Dis       |
| target       | Cat       |
