# Credit_Risk_Analysis

**Using Machine Learning to solving a real-world problem: credit card risk.**

## **Overview**

**The purpose of this assignment is use Supervised Machine Learning to test how models are able to assess credit card risk. Models such as RandomOverSampler, SMOTE,
CluserCentroids, SMOTEENN, BalancedRandomForestClassifier, & EasyEnsembleClassifier are all included.**

## **Machine Learning Results:**

### **Random OverSampling**

![Random OverSampling](https://user-images.githubusercontent.com/91576834/155634005-c440ecf3-08a5-439e-aa42-f6514077c617.png)

***Balanced Accuracy Score:*** **≈65%**

**High risk Performace:**
- **precision is very low (0.01)**

- **recall is good (0.62)**

**Low risk Performace:**
- **precision is perfect (1.00)**

- **recall is good (0.68)**



### **SMOTE OverSampling**

<img src="img/SMOTE Oversampling .png">

***Balanced Accuracy Score:*** **≈64%**

**High risk Performace:**
- **precision is very low (0.01)**

- **recall is good (0.63)**

**Low risk Performace:**
- **precision is perfect (1.00)**

- **recall is good (0.66)**


### **Cluster Centroid**

<img src="CusterCentroids .png">

***Balanced Accuracy Score:*** **≈64%**

**High risk Performace:**
- **precision is very low (0.01)**

- **recall is fair (0.59)**

**Low risk Performace:**
- **precision is perfect (1.00)**

- **recall is bad (0.44)**


### **SMOTEENN (Over & Under) Sampling**

<img src="img/ SMOTEENN .png">

***Balanced Accuracy Score:*** **≈51%**

**High risk Performace:**
- **precision is very low (0.01)**

- **recall is good (0.70)**

**Low risk Performace:**
- **precision is perfect (1.00)**

- **recall is fair (0.57)**


### **Balanced Random Forest Classifier**

<img src="img/Balanced Random Forest Classifier.png">

***Balanced Accuracy Score:*** **≈78%**

**High risk Performace:**
- **precision is very low (0.04)**

- **recall is good (0.67)**

**Low risk Performace:**
- **precision is perfect (1.00)**

- **recall is very good (0.91)**


### **Easy Ensemble Classifier**

<img src="img/Easy Ensemble AdaBoost Classifier.png">

***Balanced Accuracy Score:*** **≈93%**

**High risk Performace:**
- **precision is very low (0.07)**

- **recall is very good (0.91)**

**Low risk Performace:**
- **precision is perfect (1.00)**

- **recall is very good (0.94)**

## **Sumamry**

**The F1 score, also called the harmonic mean, can be characterized as a single summary statistic of precision and sensitivity. There is usually a trade-off between sensitivity and precision, and that a balance must be struck between the two. Based on the F1 scores the best Machine Learning Model is the Easy Ensemble Classifier with an average scare of 0.97 or 97%, followed by the Balanced Random Forest Classifier. While the worst performing model is Cluster Centroid with an average F1 score of 0.60 0r 60%.**

**Based on the model performances the Easy Ensemble Classifier model is greatly recommended for assessing credit risk.**

