# SC1015-Mini-Project (Diabetes Analysis)

## About:
This is a Mini-Project for SC1015: Introduction to Data Science and Artificial Intelligence, meant to analyse various lifestyle factors that might have an impact on one's risk of diabetes. The dataset used is from [Diabetes Health Indicators Dataset](https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset).

The brief walkthrough of our project is:

1. **Context**
2. **Data Extraction**
3. **Binary Data (Statistical Exploration)**
4. **Binary Data (Support Vector Machine)**
5. **Numerical Data (Statistical Exploration)**
6. **Numerical Data (Multi-Layer Perceptron)**
7. **One-Hot Encoded Data (Statistical Exploration)**
8. **One-Hot Encoded Data (Random Forest Classifier)**
9. **Conclusion**

## Brief Context:
Diabetes is a chronic disease in which blood sugar levels are above normal. Over time, if uncontrolled, the high levels of blood sugar can damage nerves and blood vessels, leading to serious health complications such as heart disease, stroke, blindness and amputations. There are two main typess of diabetes. While Type 1 usually occurs due to genetic disposition, Type 2 diabetes, is often caused by lifestyle habits, such as an excessive consumption of processed sugar. 

## Problem Definition:
- Are we able to predict if someone has diabetes based on their health indicators and lifestyle factors?

## Models Used:
- Support Vector Machine (SVM)
- Classification Tree
- Logistic Regression
- Multi-Layer Perceptron (MLP)
- Random Forest Classifier (RF)

## Conclusion:
- most significant numeric data: BMI
- most significant binary data: HighBP
- most significant one-hot encoded data: GenHlth
- the three factors are closely related, in that habits that cause HighBP and high BMI often lead to poor GenHlth
- suggestion: cultivating habits for a healthy lifestyle, hence improving GenHlth leads to lower risk of diabetes

## Individual Contribution:
- Tan Yichen: Binary data analysis
- Wong Kwan Kit: Numeric data analysis
- Ryan Phua Rui En: One-hot encoded data analysis

## References:
- https://www.ibm.com/topics/random-forest#:~:text=Random%20forest%20is%20a%20commonly,both%20classification%20and%20regression%20problems
- https://www.datacamp.com/tutorial/understanding-logistic-regression-python?utm_source=google&utm_medium=paid_search&utm_campaignid=19589720821&utm_adgroupid=157156375191&utm_device=c&utm_keyword=&utm_matchtype=&utm_network=g&utm_adpostion=&utm_creative=684592139660&utm_targetid=dsa-2218886984100&utm_loc_interest_ms=&utm_loc_physical_ms=9062499&utm_content=&utm_campaign=230119_1-sea~dsa~tofu_2-b2c_3-row-p1_4-prc_5-na_6-na_7-le_8-pdsh-go_9-na_10-na_11-na&gad_source=1&gclid=Cj0KCQjwk6SwBhDPARIsAJ59GwfsEeYw26RpLugpyiGQpGLr9cvo2lDalqwt0EVJPdlFMbG7hrdjxDAaAgljEALw_wcB
- https://www.datacamp.com/tutorial/multilayer-perceptrons-in-machine-learning
- https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html
- https://scikit-learn.org/stable/modules/generated/sklearn.neural_network.MLPClassifier.html
- https://scikit-learn.org/stable/modules/svm.html
- https://www.betterhealth.vic.gov.au/health/conditionsandtreatments/diabetes-and-insulin
- https://www.channelnewsasia.com/singapore/war-against-diabetes-singapore-doctors-seeing-rise-young-patients-below-40-lifestyle-habits-stress-early-screening-treatment-3921976#:~:text=HABITS%2C%20EARLY%20SCREENING-,More%20than%20400%2C000%20people%20in%20Singapore%20live%20with%20diabetes%2C%20with,to%20control%20blood%20sugar%20levels
- https://www.who.int/news-room/fact-sheets/detail/diabetes
- https://www.datacamp.com/tutorial/svm-classification-scikit-learn-python?utm_source=google&utm_medium=paid_search&utm_campaignid=19589720821&utm_adgroupid=157156375191&utm_device=c&utm_keyword=&utm_matchtype=&utm_network=g&utm_adpostion=&utm_creative=684592139660&utm_targetid=dsa-2218886984100&utm_loc_interest_ms=&utm_loc_physical_ms=9062504&utm_content=&utm_campaign=230119_1-sea~dsa~tofu_2-b2c_3-row-p1_4-prc_5-na_6-na_7-le_8-pdsh-go_9-na_10-na_11-na&gad_source=1&gclid=CjwKCAjw26KxBhBDEiwAu6KXtyQgyyTLli2nCaybYbt2svVXXmHJDpKv2y4kLAhCl9ce-SqppceMwBoCv2AQAvD_BwE
