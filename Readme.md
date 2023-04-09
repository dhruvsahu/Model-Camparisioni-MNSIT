# MNIST DATABASE of handwritten digits

## Description

The MNIST database of handwritten digits, available from this page, has a training set of 60,000 examples, and a test set of 10,000 examples. It is a subset of a larger set available from NIST. The digits have been size-normalized and centered in a fixed-size image.

We have used four different models to classify the MNSIT data. Knn, Random Forest, SVM and Decision Tree. The accuracy of the models are as follows:

| Model | Accuracy |
| --- | --- |
| Knn | 0.97 |
| Random Forest | 0.97 |
| Decision Tree | 0.85 |
| SVM | 0.97 |

Here we can conclude that Knn, SVM and Random Forest are the best models for this dataset.

The k value of KNN with training size of 0.9 is 4 for which we got this accuracy.

The accuracy of Random Forest with training size of 0.8 is 0.97 and n_estimators value 500.

The accuracy of SVM with with training size of 0.5 is 0.97 with penalty factor C=10.

We have also compared the Risk of the SVM and Decision Trees with generalized risk. Found out the mean using MLE estimator and used linear regression techniques to compare KNN and Random Forest.

To run the code, you need to have python installed on your system. You can download it from [here](https://www.python.org/downloads/).

After installing python, you need to install the following libraries:

* numpy
* pandas
* matplotlib
* seaborn
* sklearn

You can install these libraries by running the following command in your terminal:

```bash
pip install numpy pandas matplotlib seaborn sklearn
```

Installing 

```
git clone
```

## Thank You
