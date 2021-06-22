# arvato-udacity-capstone
# Create a Customer Segmentation Report for Arvato Financial Services
## 1. Introduction
The prime goal of this project is to analyze datasets to perform a data segmentation and provide valuable insights about how customers relate to general population and design a machine learning model to predict the probability of each individual in a dataset to become a new customer.
The workflow was divided in the following sections:
- Part 0: Get to Know the Data
- Part 1: Customer Segmentation Report
- Part 2: Supervised Learning Model
- Part 3: Kaggle Competition

Finally, the results of the model were uploaded on a Kaggle competition in order to evaluate how good the model performed relative to others.
In addition, I've written a blogpost on medium with more detail and explanations available in https://marcusmvls-vinicius.medium.com/customer-segmentation-of-demographic-database-for-arvato-financial-solutions-ad9d2d96acd8

## 2. Files Description
- Arvato Project Workbook: Jupyter notebook with the whole workflow for the project
- kaggle_competition.csv: CSV file with the prediction results tha I submitted on the kaggle competition
- terms_conditions.pdf : File with terms and condition of use of the Arvato datasets provided that I agreed with
- Visuals: folder with graphs and visual I created during the project.

## 3. Results
The values observed in the column “RESPONSE” are a measure of the probability of the individual respond positively to the campaign. My resulsts showed the most of the individuals had very small chances of becoming a new customer, which is expected since the RESPONSE column in the train data is greatly unbalenced. What matters the most is that the individual with the highest scores in fact became customers and in order to check that, I submitted my results in a Kaggle competition.
As required for the project. I submitted my results to a Kaggle competition and obtained a score of 0.51459 which granted me the 360th position in the competition.

## 4. Acknowledgements
I acknowledge Udacity for providing the resources and classes that greatly improved my knowledge in Data Science and Arvato financial solutions for providing datasets of real data that made the experience of working in this project much more meaningful.
## 5. References
I acknowledge the following sources, websites, github projects and blogposts for helping me in this work:
- How to define the optimal value of clusters with K-means algorithm — https://jtemporal.com/kmeans-and-elbow-method/
- Principal Component Analysis concepts and examples — https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html
- AUC-ROC curve explained — https://www.analyticsvidhya.com/blog/2020/06/auc-roc-curve-machine-learning/
- roc_auc_score sklearn reference — https://scikit-learn.org/stable/modules/generated/sklearn.metrics.roc_auc_score.html
- Insight about good binary classification models — https://machinelearningmastery.com/types-of-classification-in-machine-learning/
