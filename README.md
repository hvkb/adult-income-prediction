# Adult-Income-Prediction
The purpose of this project is to predict whether income exceeds $50K/yr based on data extracted from the 1994 US census.
Dataset link: https://www.kaggle.com/uciml/adult-census-income

## Listing of attributes ##

class label: >50K, <=50K. <br />

age: continuous. <br />
workclass: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked. <br />
fnlwgt: continuous. <br />
education: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool. <br />
education-num: continuous. <br />
marital-status: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse. <br />
occupation: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces. <br />
relationship: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried. <br />
race: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black. <br />
sex: Female, Male. <br />
capital-gain: continuous. <br />
capital-loss: continuous. <br />
hours-per-week: continuous. <br />
native-country: United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands. <br />

## Models Implemented ##
Logistic Regression Classifier </br>
Decision Tree Classifier </br>
Bagging Classifier </br>
AdaBoost </br>
AdaBoost + Random Forest Classifier </br>
Gradient Boosting Classifier </br>
XGBoost </br>
Stacking (XGBoost, Bagging, LogisticRegression) </br>

## Metrics Used ##
The following metrics were used to evaluate the performance of the models: 
1. Accuracy
2. Precision
3. Recall
4. ROC AUC: The receiver operating characteristic curve summarizes all of the confusion matrices that each threshold produces. In general, if the area under the ROC curve (AUC) is greater than that of another, the one with the greater area is better.


## Summary ##
Among the models implemented before resampling, XGBoost gave an accuracy of 85% and a precision 81%. However, the recall (>50K income) for it was only 59%, meaning, out of all the instances that were supposed to be classified as having an income of >50k, only 60% were actually classified as that. 
Among the algorithms implemented on the resampled data, Gradient Boosting Classifier performed best with an accuracy of 82.76% and a recall (>50k) and precision (>50k) of 82% and 64%, respectively. XGBoost had similar results. While the recall improved in the models trained on the resampled data, precision and accuracy went down. 
In addition, the models might not accurately work in today’s world as the data used to build them is from the 1994 census. 
"# adult-income-prediction" 
"# adult-income-prediction" 
"# adult-income-prediction" 
"# adult-income-prediction" 
"# adult-income-prediction" 
