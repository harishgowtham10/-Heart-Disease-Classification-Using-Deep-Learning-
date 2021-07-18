# Heart-Disease-Classification-Using-Deep-Learning-

## DATA SET:

The dataset is provided by Cleveland healthcare for research purpose. The dataset is uploaded in Microsoft Azure and the model is deployed in the same with the help of ML + AI Studio resource.

The data set has been taken from UCI repository:
(https://archive.ics.uci.edu/ml/datasets/Heart+Disease)
The data set contains 14 attributes – 13 features and 1 target. All 13 variables have been taken for classification.
1. age - age in years
2. sex - (1 = male; 0 = female)
3. cp - chest pain type
4. trestbps - resting blood pressure (in mmHg on admission to the hospital)
5. chol - serum cholestoral in mg/dl
6. fbs - (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
7. restecg - resting electrocardiographic results
8. thalach - maximum heart rate achieved
9. exang - exercise induced angina (1 = yes; 0 = no)
10. oldpeak - ST depression induced by exercise relative to rest
11. slope - the slope of the peak exercise ST segment
12. ca - number of major vessels (0-3) colored by flourosopy
13. thal - 3 = normal; 6 = fixed defect; 7 = reversable defect
14. target - 1 or 0

## HISTOGRAM:

The Histogram for each variable is plotted to summarize discrete or continous data.

![image](https://user-images.githubusercontent.com/47297271/126052316-afda0413-8aca-4e54-bb76-90e99186eb17.png)



## DEEP LEARNING USING NEURAL NETWORKS (NN):

Deep Learning is a subfield of machine learning concerned with algorithms inspired by the structure and function of the brain called artificial neural networks. The human brain consists primarily of nerve cells called neurons, linked together with other neurons via stand of fiber called axons. Neural Networks learn how to transform input data in to a desired response, so they are widely used for pattern classification. With one or two hidden layers, they can approximate virtually any input-output map. It has been shown to approximate the performance of optimal statistical classifiers in difficult problems. The most popular static network in the multilayer. The multilayer is trained with error correction learning, which is appropriate here because the desired multilayer response is the arteriography result and as such known.

Here, a Categorical classification model which was trained for 242 samples and validated for 61 samples in 200 epochs.

## MODEL ACCURACY:

![image](https://user-images.githubusercontent.com/47297271/126052328-0d72a3a4-ee42-40fc-8cd8-1d5e2c7f517b.png)


## MODEL LOSS:

![image](https://user-images.githubusercontent.com/47297271/126052332-ee7c2fda-ec9e-4b4a-ab39-2f64f9c09a06.png)

## RESULTS:

The loss is calculated on training and validation and its interpretation is based on how well the model is doing in these two sets. An accuracy rate is found to measure the
algorithm’s performance in an interpretable way. The categorical model had an accuracy of 78.7%. Other evaluation metrics values are shown below:

![image](https://user-images.githubusercontent.com/47297271/126052337-66482a2c-7d68-4b2d-be37-7ba63ed8511b.png)

The precision rate for having heart diseases and does not have a disease is 1 and 0.67 respectively which tells these percentage of results are relevant. High precision relates
our low false positive rate. The recall rate for having heart diseases and diseases and does not have a disease is 0.63 and 1 respectively
which tells the total relevant results classified the algorithm.
