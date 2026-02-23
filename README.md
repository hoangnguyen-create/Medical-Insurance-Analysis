# Medical Insurance Analysis
This project aims to predict the medical insurance costs billed to the individual. The charges can vary based on several factors such as the individual's age, BMI, smoking status, number of children, and region of residence.

Dataset: https://raw.githubusercontent.com/sca-programming-school/datasets/main/insurance.csv

### Pipeline summary: 

1. Data extraction
2. Convert Categorical data to Numeric
3. Build a regression model
4. Adjust the model
5. Forecasting

### Data sample: 
<img width="494" height="195" alt="image" src="https://github.com/user-attachments/assets/dbe1c1c0-9d7b-48a4-a188-e6d8e0636075" />

After cleaning and convert: 
<img width="881" height="201" alt="image" src="https://github.com/user-attachments/assets/11bd2bd3-b427-46b8-81c8-21f5c5988a5c" />

### Result: 
<img width="673" height="526" alt="image" src="https://github.com/user-attachments/assets/fa08df6d-7483-41cf-8e5e-37324f38ed4f" />

Based on the first regression model, both sex and Northwest region don't have a strong evidence supporting their affect insurance charges 

The second regression model exclude those two insignificant features: 

<img width="672" height="485" alt="image" src="https://github.com/user-attachments/assets/cf9fc222-3634-452c-8da0-dc00b7cb3475" />

### Model Evaluation:

* The regression model explains approximately 75% of the variance in medical charges (R² = 0.751).
* Smoking status is the strongest predictor, increasing expected medical charges by approximately $23,800.
* Age and BMI significantly increase insurance costs.
* The number of children also has a positive impact on charges.
* Regional effects are relatively minor compared to lifestyle and demographic factors.

Link to whole project via Google Collab: https://colab.research.google.com/drive/1PHNKSgUcKFl1a0msLQcWcl17H-TuYCqI?usp=sharing#scrollTo=P_GKyv41r6up
