******Determinants of Customer Churn in E-commerce: An Econometric Analysis******

Full report: https://rpubs.com/Trang_Hoang/1360998

**Overview**

This study investigates the determinants of customer churn in e-commerce using a binary logistic regression model on a real-world dataset from Kaggle. The goal is to identify which behavioral, demographic, and experiential factors most strongly predict whether a customer will stop using an online platform.

**Key Objectives**

Quantify the relationship between customer behavior (orders, complaints, engagement) and churn.

Evaluate how demographics (age, marital status, city tier) and product preferences influence loyalty.

Provide data-driven insights for customer retention and churn mitigation strategies.

**Methodology**

After extensive data cleaning and transformation, the model was estimated using a binary logit approach, chosen over the probit alternative for superior fit (AIC = 1925 vs 1968). Continuous variables were log-transformed to address skewness, and multicollinearity was tested using VIF diagnostics. Model refinement followed a general-to-specific approach, removing insignificant predictors through sequential likelihood ratio and Wald tests.

**Major Findings**

Complaints significantly increase churn likelihood (+16.6 pp).

Longer tenure and recent purchases lower churn probability (−15.6 pp and −8.1 pp respectively).

Delivery distance and multiple addresses raise churn risk.

Single customers are 2.3× more likely to churn than married ones.

Preference for mainstream products (mobile phones, laptops) decreases churn, while niche “Other” categories show the highest risk (+27.3 pp).

Surprisingly, higher satisfaction scores slightly increase churn, suggesting complex behavioral dynamics or measurement bias.

**Model Performance**

Accuracy: 88.9% AUC: 0.90

McFadden R²: 0.44 McKelvey–Zavoina R²: 0.62

Sensitivity: 94.85% Specificity: 68.93%
These results confirm strong discriminative power and robust predictive validity for churn behavior.

**Implications**

This research highlights that churn is multifactorial, driven by behavioral, experiential, and demographic factors. Practical implications include:

Enhancing complaint resolution systems to retain at-risk users.

Leveraging customer segmentation by purchase category and city tier.

Developing predictive churn models integrating econometric insights with machine learning for future improvement.
