# DATA698-Research-Project-Proposal

## A Comparison of Machine Learning Classification Algorithms: Modelling Customer Churn Prediction

### Introduction
Every company wants to be successful and to do so, they must focus on retaining and increasing their customer base. Oftentimes when a company’s marketing strategies do not meet the interest of current customers it is not uncommon to see these customers defect from their product. Customer retention varies depending on the type of product or service offered, type and size of the targeted consumers and how the company plans to expand their business. 

Tracking customer churn is easiest to monitor from subscription business which is why this research will examine the attributes of credit card companies, internet service providers and telecommunication companies. This project will also attempt to experiment using different supervised learning methods including but not limited to Regression, Trees, Support Vector Machine and Neural Networks.

### Literature Review
Customer churn can be referred to the phenomenon whereby a customer leaves a service provider (Au et al., 2003). It is represented as the percentage of customers an organization loses over a given period (monthly, quarterly, annually et cetera). This is done by taking the number of customers a company lost and divide that by the total number of customers the company had at the beginning of that period.

Predictive modeling encourages organizations to use Big Data which consists of diverse sources of historical data to predict future events or perspectives of the customer. Customer churn prediction is one of the most useful areas of study in data analytics when identifying the potential defections of existing customers. Due to the large amount of data available for such predictions, machine learning and data mining have been heavily used in this domain. Data mining goes as far as extracting knowledge and insights while machine learning focuses on comparing the different models to predict churn. 

(Kaur et al., 2013) provided a detailed guideline for changing customer's raw data and converting it into useful information using data mining techniques. They applied the naive Bayes, decision tree and support vector machine classifier to recognize significant customer attributes to predict churn. This research found that the prediction success rate of churn class is more than the prediction success rate of loyal class. 
There are various features involved when predicting churn. These features are categorized under two variables: transaction and demographic variables (Madushanka et al., 2015). Transaction features include recency, frequency, and monetary value of the transaction. Recency describes how recently a customer has made a purchase, frequency describes how often a customer makes a purchase and monetary value is how much money a customer spends on purchases. On the other hand, demographic features include information about the customer such as geographical, ethnicity, religion, income level, occupation, and gender. These factors are often considered to make data mining more relevant when exploring the data. 

Additionally, customer churn prediction is an important research discipline for businesses where it is a lot more profitable to retain and satisfy existing customers than to attract new customers for several reasons: (1) Long term relationships with customers which allow companies to focus on their customer needs instead of looking for new while potentially weeding out the bad-fit customers; (2) Customers who leave the company can influence other customers within their social network to do the same (Nitzan & Libai, 2011); (3) long term customers tend to buy more and they can refer people to the company by positive word of mouth (Ganesh et al., 2000. Overall, customer churn prediction is necessary as a retention strategy.

### Purpose of Study
The purpose of this study is to leverage data insights and predictive modeling on improving customer retention using various machine learning algorithms. If we can identify which customers are most likely to leave and why, we can proactively focus our marketing efforts on retaining them. This research will focus on the following questions:
1.	What features can be used in building a better predictive model for customer churn?
2.	If applicable, how does imbalanced data affect model results and how to handle it?
Imbalanced data typically refers to a classification problem where there is a disproportionate ratio of observations in each class. Most machine learning algorithms work best when the samples in each class are equal as they are designed to maximize accuracy and reduce error.

### Methodology
This type of research is a quantitative research where evidence provided will be evaluated using statistics and results are presented in tables and graphs. Churn data is private to companies therefore very few datasets are available. However, a total of four (4) datasets are retrieved from the Kaggle, a public database which helps in making this research possible. The researcher will analyze the data collected using R to do descriptive analysis and apply the models to each dataset. Remote bibliographical databases are used for searching research articles and journals related to customer churn and machine learning.  

### Evaluation
Model Evaluation is an essential part of the model development process. It helps to find the best model that represents our data and how well the chosen model will work in the future. According to the models’ output, they will be measured based on their accuracy. Methods that will be used includes the Confusion Matrix, Area Under the Curve (AUC) and Lift charts. Results from various machine learning algorithms used will be compared to see which model best fit the data. The results may vary based on the dataset provided. 

### References
Madushanka, Tiroshan & Senanayake, Damith & Mendis, Laksheen & Muthugama, Lakmal. (2015). Customer Churn Prediction: A Cognitive Approach. International Journal of Computer, Electrical, Automation, Control and Information Engineering. 9. 753 - 759.
Arno De Caigny, Kristof Coussement, Koen W. De Bock,  A new hybrid classification algorithm for customer churn prediction based on logistic regression and decision trees, European Journal of Operational Research, Volume 269, Issue 2, 2018, Pages 760-772, ISSN 0377-2217, https://doi.org/10.1016/j.ejor.2018.02.009. (http://www.sciencedirect.com/science/article/pii/S0377221718301243)
Nitzan I, Libai B. Social Effects on Customer Retention. Journal of Marketing. 2011;75(6):24-38. doi:10.1509/jm.10.0209
Ganesh, Jaishankar & Arnold, Mark & Reynolds, Kristy. (2000). Understanding the Customer Base of Service Providers: An Examination of the Differences Between Switchers and Stayers. Journal of Marketing - J MARKETING. 64. 65-87. 10.1509/jmkg.64.3.65.18028.
Au, T., Li, S., &amp; Ma, G. (2003, June 01). View of Applying and Evaluating Models to Predict Customer Attrition Using Data Mining Techniques: Journal of Comparative International Management. Retrieved September 08, 2020, from https://journals.lib.unb.ca/index.php/jcim/article/view/442/735
Kaur, M., Singh, K., & Sharma, N. (2013). Data Mining as a tool to Predict the Churn Behaviour among Indian bank customers.

