# Breast-Cancer-Classification

## About the Project
### Data Used

Mammogram Dataset:
  - Elter, M., & Schulz-Wendtland, D. R. (n.d.). Mammographic Mass Data Set. UCI Machine Learning Repository: Mammographic mass data set. Retrieved July 17, 2022, from https://archive.ics.uci.edu/ml/datasets/mammographic+mass

### Short Description
Breast cancer accounts for 14% of all cancer deaths in Canada but can be successfully treated if detected early. Mammograms check for the presence of unusual masses in the breast, and doctors use these results to recommend whether further tests are required. Current assessment approaches are not very effective, resulting in a large number of unnecessary procedures. By using Logistic Regression, Decision Trees, and K-Nearest Neighbours, we are able to see how supervised models can determine whether a mass indicated in a mammogram is benign or malignant.

### Objectives
The purpose of this project is to use machine learning models to predict the possibility of breast cancer based on the attributes from patients’ mammogram results. Creating a reliable prediction model will help detect the cancer in the earlier stages and reduce the need for unnecessary invasive procedures. 

### Performance Parameters
Receiver Operating Characteristic (ROC) curves were plotted for each set of model predictions to compare performance. The ROC curve is used to plot the true positive versus the false positive rates to illustrate the sensitivity of the model. An ROC curve that is closer to the top left corner indicates that the model is doing better at classifying data into the appropriate categories. The Area Under the Curve (AUC) was calculated for each model, and it was determined that with an AUC of 0.84, the logistic regression model outperformed both the decision tree (AUC = 0.80) and the K- nearest neighbours (AUC = 0.79).

### Results
The results indicated that each of the models outperformed the BI-RADS assessment with respect to accuracy and precision, and greatly reduced the proportion of cases incorrectly classified as malignant.

### Conclusions
Machine learning methods appear to outperform BI-RADS assessment in successfully classifying mammogram masses as benign or malignant. Improvements can be made with more data, grouping models, or exploring other classification models (ex. Random Forests, Support Vector Machines, Neural Networks, etc)


### Installation & Execution
1. Download both the .ipynb and the .data files from this repository.
2. Open Jupyter Notebooks and upload these two files in the same directory.
3. Run all the code in the file with no issues being displayed.

### Licenses
To create the code for this project we used Jupyter Notebooks from Wilfrid Laurier's domain which can be accessed [here](https://wlu.syzygy.ca).
To access, need to log in with Laurier credentials in order to use the website's functions 
