## Chicago Crime Classification with Machine Learning


## Dataset
https://data.cityofchicago.org/Public-Safety/Crimes-2019/w98m-zvie/data


## Programming Platform:
* Python

## Used Libraries:
* Data Analysis and cleaning: Pandas, NumPy, SciPy 
* Data Visualization: Matplotlib, Seaborn
* Machine Learning: Scikit-learn

In this project, machine learning (ML) algorithms were implemented for determining the severity of the crime and, also for classifying the crime. The ML algorithms that were implemented are:

* K-Nearest Neighbor (KNN)
* Logistic Regression
* Support Vector Machine (SVM)
* KMeans clustering (Unsupervised)

The dataset that was used here is an imbalanced dataset (rare class - 3%). So, like any rare case prediction, implementing ML algorithms to classify crimes is difficult. To deal with the imbalanced dataset, undersampling, and oversampling techniquse were implemented. Althogh the undersampling technique resulted in a poor performance, oversampling technique with class weight setting worked satisfactorily.  

Throught the notebook each section is described before the implementation of the codes.



