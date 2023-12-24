# Customer-Churn-Prediction-Analysis-and-Customer-Retention-LP2-Project
This repository contains a data analysis on the churn rate of customers of Vodafone

# Title
### PREDICTIVE MODELLING OF CUSTOMER CHURN AND RETENTION STRATEGIES FOR A TELECOMMUNICATION COMPANY: AN ANALYSIS FOR VODAFONE CORPORATION

# Table of Content
- Project Description
- Definition of Churn and its Significance
- Objective of the Project
- Project Approach
- Data Description
- Project Summary
    - Business Understanding
    - Data Understanding
    - Data Preprocessing
    - Exploratory Data Analysis
    - Hypothesis Testing
    - Feature Engineering
    - Modeling and Evaluation
    - Handling Imbalanced Data
    - Selection of Best Model
    - Future Prediction on Test Set
- Technologies Used
- Conclusion
- Recommendations
- License
- Social Media
- Acknowledgement
- Authors
- Contact 

## Project Description
In today's competitive landscape, businesses, especially in telecommunications, face the challenge of retaining customers. Customer churn, the rate at which customers leave a service provider, poses a significant threat to sustained profitability and growth. To combat this issue, leveraging data-driven insights and machine learning techniques becomes imperative.

This project delves into analyzing historical customer data to discern patterns and factors contributing to churn. By harnessing the power of machine learning, it aims to build predictive models that accurately anticipate customer churn. Such models can assist in devising targeted retention strategies, ultimately empowering telecommunications companies to mitigate customer attrition and bolster profitability.


## Importance of Customer Retention Strategies and the Significance of churn
Customer retention holds immense importance in the telecommunications sector. Acquiring new customers often incurs higher costs compared to retaining existing ones. Consequently, strategies aimed at preserving customer loyalty directly impact a company's revenue and long-term viability.
By investing in effective retention strategies, companies not only reduce the financial strain associated with acquiring new customers but also foster a loyal customer base. Retained customers tend to be more engaged, make repeated purchases, and potentially advocate for the brand, thereby augmenting the company's reputation and market presence.
Customer churn represents the rate at which customers discontinue their association with a service or product. Understanding and mitigating churn is crucial for several reasons:
1.	Financial Impact: Churn directly affects revenue and profitability. Losing customers means losing their associated revenue streams. The cost of acquiring new customers is notably higher than retaining existing ones, making churn reduction financially advantageous.
2.	Market Competition: In competitive industries like telecommunications, retaining customers is essential. High churn rates can signify dissatisfaction or better offerings from competitors, impacting a company's market standing.
3.	Customer Lifetime Value: Retaining customers over the long term contributes significantly to their lifetime value. Loyal customers tend to make more purchases and generate higher revenue over their engagement period.
4.	Brand Image and Loyalty: Excessive churn can harm a brand's reputation. Retained customers often serve as brand advocates, contributing to positive word-of-mouth marketing.
5.	Operational Stability: Predictable customer retention allows for better forecasting and planning, ensuring stability in business operations and resource allocation.
6.	Data Insights: Analysing churn factors provides insights into customer behaviour, preferences, and pain points. This knowledge aids in refining products/services and developing more targeted retention strategies.
7.	Sustainability and Growth: Reduced churn leads to more sustainable growth. A loyal customer base provides a foundation for expansion and innovation.


## Objective of the Project
 The primary objective of this project is to develop robust machine-learning models capable of accurately predicting customer churn. By scrutinizing historical customer data, the aim is to identify crucial churn indicators and discern underlying patterns contributing to customer attrition.


## Project Approach
The CRISP-DM framework is indeed a robust methodology which is widely utilized in data mining and analysis projects. Its structured approach ensures a systematic and comprehensive handling of complex data-related challenges, allowing for a thorough understanding of the data and facilitating the generation of meaningful and actionable insights. By following the CRISP-DM framework, the project benefited from a well-defined roadmap that encompassed various stages as follows:

- Introduction and Objective
- Business Understanding
- Data Understanding
- Data Preprocessing
- Exploratory Data Analysis
- Hypothesis Testing
- Data Preparation and Feature Engineering
- Machine Learning Model
- Evaluation
- Results of Model
- Conclusion and Recommendations
- References

### Data Description
1.	Gender: Whether the customer is a male or a female
2.	SeniorCitizen: Whether a customer is a senior citizen or not
3.	Partner: Whether the customer has a partner or not (Yes, No)
4.	Dependents: Whether the customer has dependents or not (Yes, No)
5.	Tenure: Number of months the customer has stayed with the company
6.	Phone Service: Whether the customer has a phone service or not (Yes, No)
7.	MultipleLines: Whether the customer has multiple lines or not
8.	InternetService: Customer's internet service provider (DSL, Fiber Optic, No)
9.	OnlineSecurity: Whether the customer has online security or not (Yes, No, No Internet)
10.	OnlineBackup: Whether the customer has online backup or not (Yes, No, No Internet)
11.	DeviceProtection: Whether the customer has device protection or not (Yes, No, No internet service)
12.	TechSupport: Whether the customer has tech support or not (Yes, No, No internet)
13.	StreamingTV: Whether the customer has streaming TV or not (Yes, No, No internet service)
14.	StreamingMovies: Whether the customer has streaming movies or not (Yes, No, No Internet service)
15.	Contract: The contract term of the customer (Month-to-Month, One year, Two year)
16.	PaperlessBilling: Whether the customer has paperless billing or not (Yes, No)
17.	Payment Method: The customer's payment method (Electronic check, mailed check, Bank transfer(automatic), Credit card(automatic))
18.	MonthlyCharges: The amount charged to the customer monthly
19.	TotalCharges: The total amount charged to the customer
20.	Churn: Whether the customer churned or not (Yes or No)

 
## Project Summary
### Data Preprocessing
The data underwent extensive preprocessing, including handling missing values and transforming categorical variables for compatibility with modeling techniques. Imputation strategies were utilized to address missing values, while categorical variables underwent encoding for effective integration into the models.

### Exploratory Data Analysis
EDA provided valuable insights into data distributions, variable relationships, and notable patterns. It offered key revelations regarding customer churn trends, correlations among variables, and enabled a comprehensive gender-based analysis, enhancing our understanding of the dataset.

### Hypothesis Testing
The project conducted rigorous hypothesis testing to gauge the influence of variables on churn. Employing statistical methods like chi-square and logistic regression, we assessed the relationships between categorical variables and churn. Additionally, numerical variables' impact on churn was analyzed through logistic regression, unveiling crucial insights.

### Feature Engineering
Feature engineering was a critical phase, involving the creation of new variables, categorical variable encoding, and meticulous feature selection and domain knowledge. This process ensured the inclusion of the most relevant features for modeling purposes.

### Modeling and Evaluation
The project encompassed training and evaluating various machine learning algorithms like Logistic Regression, Decision Trees, Random Forest, XGBoost, and Support Vector Machines. Assessment metrics included precision, recall, F1-score, and accuracy, providing a comprehensive understanding of model performance and suitability for addressing churn-related challenges.

### Handling Imbalanced Data
Strategies like class weighting and SMOTE (Synthetic Minority Over-sampling Technique) were implemented to tackle class imbalance, particularly enhancing the performance of models on the minority class denoting churned customers.

### Selection of Best Model
The selection of the best model relied on a comprehensive evaluation considering precision, recall, and F2-score. Further, the chosen model underwent rigorous k-Fold cross-validation to ensure its robustness in handling new data. Hyperparameter tuning aimed at striking the right balance between bias and variance, resulting in a well-generalizing model.

### Future Prediction on Test Set
Employing the chosen best model, predictions for churn were made on the test set, which comprised unseen data. The resultant predictions were aggregated into a results DataFrame, subsequently merged with the original test set for deeper analysis.

### Conclusion and Recommendations
The project concludes by providing actionable insights and tailored recommendations specifically designed for telecommunication companies. These recommendations are geared towards significantly reducing churn rates, strengthening customer retention strategies, and ultimately fine-tuning the overall business outcomes.


|Code|Name of Project|Published Article|Deployed App|
|:---|:-------------:|:---------------:|-----------:|
|LP2 |Churn |https://medium.com/@niidoku/predictive-modelling-of-customer-churn-and-retention-strategies-for-a-telecommunication-company-an-93d8aaad1229

## Setup
- Programming Language: Python
- Data Manipulation and Analysis Libraries: Pandas, NumPy
- Data Visualization Libraries: Matplotlib, Seaborn, Plotly 
- Machine Learning Libraries:
    - Scikit-learn
    - XGBoost
    - Random Forest
    - Support Vector Machines (SVM)
    - StatsModels
- Jupyter Notebook
- Version Control: Git and GitHub
- Text Editor / Integrated Development Environments (IDEs): Visual Studio Code
- Communication Tool: Microsoft Teams was used to collaborate with team members.
- Reporting and Visualization Tool: Tableau

### Conclusion

The analysis undertaken for Vodafone's customer churn elucidates critical facets influencing customer attrition within the telecommunications domain. The project's primary objective was to predict churn accurately, offering insights into mitigating this challenge and fostering sustainable growth.

### Recommendations

1.	Promote Long-term Contracts: Encourage longer-term contracts to potentially reduce churn. Highlight benefits and incentives associated with extended contracts.
2.	Payment Method Optimization: Promote alternative payment methods that correlate with lower churn rates, emphasizing the advantages to customers.
3.	Enhanced Service Offerings: Focus on improving and marketing services like Fiber Optic internet and phone services to enhance customer retention.
4.	Senior Citizen Engagement: Tailor retention strategies to engage and retain senior citizen customers based on their lower churn rates.



### License
MIT Lincense

### Social Media
Medium

### Acknowledgement
A hearty appreciation to the entire Azubi Team for your continuous support and same goes to Team Odyssey for the hard work and dedication.

### Authors
- Reginald Ffoulkes Crabbe
- Efosa Dave Omosigho
- Alexander Ndunda
- Isaac Mawuli Fumey
- Prince Eyram Kofi Adzanku
- Marufu Loveness Enesia
