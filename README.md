# Churn-Bank-Analysis-and-Classification

In this project, we aim to analyze a provided dataset related to bank customer turnover, commonly referred to as 'bank churn.' By examining historical records, we intend to uncover underlying trends and patterns capable of forecasting whether a given bank client might discontinue their relationship with the organization. Applying advanced analytics and machine learning algorithms, our findings could enable banks to devise proactive measures aimed at reducing churn rates, boosting loyalty, and refining customer engagement tactics. Ultimately, these efforts would lead to improved business outcomes and enhanced value delivery across all stakeholders involved.

#### Notebook at My Kaggle Profile
<https://www.kaggle.com/code/junaidullhassan/churn-analysis-gradiantboosting-acc-88-auc-89>

## Key Technologies & Libraries Used

* Python
* Jupyter Notebook
* scikit-learn
* seaborn
* Numpy
* Pandas
* matplotlib

## About Churn Analysis
Churn analysis, also known as customer attrition or customer churn prediction, refers to evaluating historical customer behavior and identifying factors leading to customers ceasing their association with a company or service provider. Utilizing statistical models and machine learning algorithms, organizations apply churn analysis to anticipate future defections accurately. Early detection allows companies to implement strategic interventions designed to maintain satisfied customers, thereby fostering loyalty, safeguarding revenue streams, and promoting sustainable growth. Common applications include telecommunications, subscription-based platforms, financial institutions, and utility providers seeking to optimize customer lifetime values and minimize negative consequences stemming from involuntary attrition.

### Key aspects of churn analysis encompass:

* Preparation and cleaning of historical datasets containing relevant variables indicative of consumer preferences, behaviors, interactions, and transaction histories.
* Feature engineering and selection to enhance predictive power via dimensionality reduction, correlation examination, and variable importance ranking methodologies.
* Application and fine-tuning of appropriate supervised modeling approaches, including logistic regression, decision trees, Random Forests, Support Vector Machines, Neural Networks, and XGBoost, among others.
* Model validation employing metrics such as accuracy, precision, recall, ROC curves, confusion matrices, lift charts, and Gini coefficients.
* Implementation and continuous monitoring of selected models to facilitate timely intervention programs targeting susceptible clients and informing organizational strategy adjustments.
* Ongoing evaluation of emerging trends and evolving customer expectations to ensure relevancy and adaptability of employed analytical frameworks.
* Ultimately, mastering churn analysis empowers businesses to foster healthier relationships with existing consumers, reduce undue expenses linked to acquiring replacement clients, and * bolster competitive advantage amidst increasingly saturated markets.

## About Dataset
To get started, grab your own copy of our curated dataset by visiting the link below:
<https://www.kaggle.com/competitions/playground-series-s4e1/data>

This dataset describes various attributes of individual customers who have accounts at a specific banking institution. It includes information about their demographics, account activity, financial history, and behavioral patterns. Let's examine each attribute closely:

* id - Each record is assigned a unique identification number.
* CustomerId - Every customer is assigned a distinct ID number serving as an internal reference for the bank.
* Surname - The last name of the customer.
* CreditScore - An assessment of a person's creditworthiness based on past payment performance. Scores generally range between 300–850; higher scores indicate lower risk associated with lending money.
* Geography - Indicates the country where the customer resides (i.e., France, Spain, or Germany).
* Gender - Identifies whether the customer is male or female.
* Age - Chronological age of the client.
* Tenure - Represents the duration (in years) since opening the first account with the bank.
* Balance - Current amount of funds held within the primary checking or savings account.
* NumOfProducts - Count of different types of financial services used by the customer (such as loans, insurance policies, etc.).
* HasCrCard - Specifies whether the customer possesses a credit card issued by the bank (1 indicates they do while 0 means otherwise).
* IsActiveMember - Signals whether the client remains actively engaged with the bank's offerings (1 denotes active status whereas 0 signals non-active membership).
* EstimatedSalary - Approximate income level derived based on employment details and publicly available statistics.
* `Exited` - Reflects whether the client terminated his/her relationship with the bank (1 represents exiting while 0 signifies still being an active customer).
By analyzing these features, banks may develop targeted marketing strategies aimed at improving customer retention, increasing product adoption, detecting early signs of potential attrition, and enhancing overall profitability.

### Enjoy exploring, and happy coding! 🎉
