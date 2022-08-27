
# Feature Selection

Data Preprocessing of high dimentional data set by using feature selection.


## Documentation

[Documentation](https://linktodocumentation)



The dataset used in the above project is "Heart_Disease_Prediction".
After analysing the dataset we observe that the dataset cointains few instances but has high dimention.

Moreover, there are some missing values as well as some garbage values. Which need to be processed before further processing of dataset.
 As Machine learning works on a simple rule — if you put garbage in, you will only get garbage to come out.

A good portion of this dataset is noise and some features might not correspond significant in predicting the output. Moreover the huge dataset will also it much time in processing.
And hence its dimention must be reduced.

1)To reduce the dimentions of dataset and hence prevent overfitting we use feature selection in this project to reduce the number of features.
As there are many redundent features. this would boost the performance of models. This would keep the curse of dimentionality in check.


2)We will use different techniques of feature selection and see the accuracy by ensembling three classifiers for better accuracy (linear regression, logistic regression, Naive Bayers) on the categorical classification




- For feature selection we use :-

1) Wrapper Methods

i}Forward Selection

ii}Backward Elimination

iii}Bi-directional Elimination


2) Filter Method

3) Embeded Method(LASSO)
## Deployment

To deploy this project run

```bash
  http://localhost:8888/notebooks/Categorical_Feature_Selection_missing_values.ipynb
```


## Authors

- [@toppnoche](https://www.github.com/octokatherine)


## Optimizations

1)Cleaning of the dataset and resoving of outliers as well of missing values, by using Data_Cleaning https://github.com/toppnoche/Data_Cleaning

2)Using ensemble learning and combining 3 classifiers to get better accuracy and least error