# Insurance-claim

✅ Project Title:
Insurance Claim Classification — Genuine or Suspicious Claims Detection

✅ Objective:
To build a machine learning model that accurately classifies insurance claims as either Genuine or Suspicious based on customer details, vehicle characteristics, claim information, and accident details.

✅ Dataset Description:
The dataset contains records of insurance claims with the following key features:

Feature	Description
Claim_ID	Unique ID for each insurance claim
Customer_Age	Age of the customer
Vehicle_Age	Age of the vehicle (in years)
Vehicle_Type	Type of the vehicle (e.g., Sedan, SUV, Truck)
Claim_Amount	Amount claimed by the customer
Accident_Type	Nature of the accident (e.g., Collision, Theft, Fire)
Police_Report	Whether a police report was filed (Yes/No)
Claim_Status	Target variable - Genuine (0) or Suspicious (1)

✅ ML Approach:
Preprocessing:

Encode categorical variables (Label Encoding).

Drop non-predictive ID column (Claim_ID).

Model Selection:

Logistic Regression for baseline.

Random Forest for improved performance.

Evaluation Metrics:

Accuracy: Proportion of correct predictions.

Precision: Correctness of positive (Suspicious) predictions.

✅ Why Random Forest Works Better:
Handles mixed data types (numeric + categorical).

Captures nonlinear relationships.

Robust to outliers and feature interactions.

✅ Business Use Case:
Insurance companies can use this model to:

Automate claim verification.

Flag potentially fraudulent (Suspicious) claims for review.

Speed up genuine claims processing.
