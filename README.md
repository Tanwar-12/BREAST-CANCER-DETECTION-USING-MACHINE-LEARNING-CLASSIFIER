# 𝐁𝐑𝐄𝐀𝐒𝐓 𝐂𝐀𝐍𝐂𝐄𝐑 𝐃𝐄𝐓𝐄𝐂𝐓𝐈𝐎𝐍 𝐔𝐒𝐈𝐍𝐆 𝐌𝐀𝐂𝐇𝐈𝐍𝐄 𝐋𝐄𝐀𝐍𝐈𝐍𝐆 𝐂𝐋𝐀𝐒𝐒𝐈𝐅𝐈𝐄𝐑
 ## INTRODUCTION :
 Breast cancer detection using machine learning classification is a project where you build a model to identify whether a given set of medical features indicates the presence of breast cancer. This project involves using a labeled dataset of medical records, where each record is classified as either indicating breast cancer or not.

## STRUCTURE THE PROJECT INTO A SERIES OF STEPS :
_**Goal of the ML project**_

_**Import essential libraries**_

_**Load breast cancer dataset & explore**_

_**Create DataFrame**_

_**EDA**_

_**Pair plot of breast cancer data**_

* Counterplot
  
* Heatmap
  
* Heatmap of breast cancer DataFrame
  
* Heatmap of a correlation matrix

* Correlation barplot
 
_**Data Preprocessing**_

_**Split DataFrame in train and test**_

_**Feature Scaling**_

_**Model Building**_

* Support Vector Classifier

* Logistic Regression

* K – Nearest Neighbor Classifier

* Naive Bayes Classifier

* Decision Tree Classifier

* Random Forest Classifier

* Adaboost Classifier

* XGBoost Classifier

_**XGBoost Parameter Tuning Randomized Search**_

_**Confusion Matrix**_

_**Classification Report of Model**_

_**Cross-validation of the ML model**_

_**Save the Machine Learning model**_

_**Conclusion**_

## **GOAL OF PROJECT**:
_**We have extracted features of breast cancer patient cells and normal person cells. As a Machine learning engineer / Data Scientist has to create an ML model to classify malignant and benign tumor.**_

####  _**IMPORTING LIBRARIES**_

### _**LOAD THE DATASET**_
**Load data in python using panda’s library**

#### _**BASIC CHECKS**_

## **DOMAIN ANALYSIS**

**Mean Radius**: This feature represents the average distance from the center to points on the perimeter of the tumor.

**Mean Texture:** It signifies the average variation in gray-scale intensities of the pixels in the image, which can correlate with the homogeneity of the tumor.

**Mean Perimeter**: This denotes the average length of the tumor boundary.

**Mean Area:** It indicates the average area of the tumor.

**Mean Smoothness:** This feature characterizes the variation in radius lengths in the tumor, providing insights into how smooth or irregular the tumor boundary is.

**Mean Compactness:** It combines the perimeter and area of the tumor to provide a measure of how compact the shape of the tumor is.

**Mean Concavity:** This represents the severity of concave portions of the contour of the tumor.

**Mean Concave Points:** It signifies the number of concave portions of the contour of the tumor.

**Mean Symmetry:** This feature quantifies the symmetry of the tumor shape.

**Mean Fractal Dimension:** It measures the complexity of the tumor shape at different scales.

**Radius Error:** This indicates the standard error of the mean of distances from the center to points on the perimeter.

**Texture Error:** It represents the standard error of variation in gray-scale intensities.

**Perimeter Error:** This denotes the standard error of the tumor perimeter.

**Area Error:** It indicates the standard error of the tumor area.

**Smoothness Error:** This represents the standard error of the variation in radius lengths.

**Compactness Error:** It denotes the standard error of the tumor compactness.

**Concavity Error:** This signifies the standard error of the severity of concave portions.

**Concave Points Error:** It represents the standard error of the number of concave portions.

**Symmetry Error:** This indicates the standard error of tumor symmetry.

**Fractal Dimension Error:** It represents the standard error of tumor shape complexity.

**Worst Radius:** This feature represents the largest distance from the center to points on the perimeter among all measurements.

**Worst Texture:** It signifies the highest variation in gray-scale intensities among all measurements.

**Worst Perimeter:** This denotes the longest tumor boundary among all measurements.

**Worst Area:** It indicates the largest tumor area among all measurements.

**Worst Smoothness:** This feature represents the smoothness of the largest tumor among all measurements.

**Worst Compactness:** It signifies the compactness of the largest tumor among all measurements.

**Worst Concavity:** This represents the severity of concave portions of the contour of the largest tumor among all measurements.

**Worst Concave Points:** It signifies the number of concave portions of the contour of the largest tumor among all measurements.

**Worst Symmetry:** This feature quantifies the symmetry of the largest tumor among all measurements.

**Worst Fractal Dimension:** It measures the complexity of the shape of the largest tumor among all measurements.

**Target:** This denotes the class label, where 0 indicates benign and 1 indicates malignant, which is the target variable for prediction.

### **EXPLORATORY DATA ANALYSIS**
