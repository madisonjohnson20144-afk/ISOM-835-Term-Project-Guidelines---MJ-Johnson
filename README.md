# Patient Appointment No-Show Prediction

## Project Overview
This project uses machine learning to predict whether patients will miss scheduled medical appointments. Missed appointments create inefficiencies in healthcare systems, and predictive analytics can help providers identify high-risk cases and improve scheduling outcomes.

## Objectives
- Predict patient no-shows using machine learning
- Identify key factors influencing appointment attendance
- Compare multiple predictive models
- Provide actionable insights for healthcare decision-making

## Dataset
Source: Kaggle – Patient Appointment No-Show Dataset  
The dataset contains over 100,000 appointment records with features such as age, gender, appointment timing, SMS reminders, and previous no-show behavior.

## Tools & Technologies
- Python
- Google Colab
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## Models Used
- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

## Results
Gradient Boosting achieved the best performance, with strong accuracy and ROC-AUC scores. Key predictors included previous no-show behavior, waiting time, and age.

## Key Insights
- Previous no-show history is the strongest predictor
- Longer waiting times increase no-show likelihood
- SMS reminders reduce missed appointments
- Younger patients are more likely to miss appointments

## How to Run
1. Open the Google Colab notebook
2. Run all cells in order
3. Review outputs and visualizations

Colab Link: https://colab.research.google.com/#fileId=https%3A//storage.googleapis.com/kaggle-colab-exported-notebooks/scratchpad/notebook5be0727968.73dbab84-e9b9-422b-9c70-6a9e4b603f9f.ipynb%3FX-Goog-Algorithm%3DGOOG4-RSA-SHA256%26X-Goog-Credential%3Dgcp-kaggle-com%2540kaggle-161607.iam.gserviceaccount.com/20260506/auto/storage/goog4_request%26X-Goog-Date%3D20260506T213050Z%26X-Goog-Expires%3D259200%26X-Goog-SignedHeaders%3Dhost%26X-Goog-Signature%3D4124d3e235ea2cf22f13b0f692f0514bd02fb9029d125c1ba7250a5ee741893de6fda9c1a2759a7609a49feca42392a50e0747bbca003e02ff7203099105cbecb04dd780912e8a40451c9417dea1dc445174bb341be78da38fc8f3d5b537f72dd3ed2adaf722f010222e62dd80a8e259332e6212b2a973cd0353feb3c489433c8dea4a3561c28c94b34df171b423450c11ab383cfeea1c5058f922a14d84538ae5c84de4ee8f9096acfc7e0d5476bf3e7808f56919640c8d37f1c722cc000a298c8771611f464556e2bb85ac868523fff8bacdc5659f232888a06d11b3ff0e3b434619c9d869e431841f394bc74034bbc8103f50d39312b198d81de19fb782f1

## Repository Structure
- data/ (dataset or link)
- notebooks/ (Colab notebook)
- visuals/ (plots)
- report/ (final PDF)
- README.md

## Conclusion
This project demonstrates how machine learning can improve healthcare operations by predicting patient no-shows and enabling proactive intervention strategies.
