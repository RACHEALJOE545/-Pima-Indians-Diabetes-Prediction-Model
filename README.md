# -Pima-Indians-Diabetes-Prediction-Model

<img width="704" height="419" alt="Screenshot 2025-10-18 131106" src="https://github.com/user-attachments/assets/113c08aa-8b1f-441f-be55-b5b0bb70b30c" />


## 📘 Introduction:

This project explores the prediction of diabetes presence among women of Pima Indian heritage, based on clinical and physiological parameters. The dataset originates from the National Institute of Diabetes and Digestive and Kidney Diseases and aims to identify risk factors and classify individuals as diabetic or non-diabetic.

The problem addresses a key healthcare challenge — early detection of diabetes to enable timely intervention and reduce complications. Using machine learning techniques, this analysis examines how patient factors such as glucose levels, BMI, and age can influence diabetes diagnosis.


## 📊 Key Metrics:

- What is the overall diabetes prevalence rate in the dataset?

- How do glucose concentration, BMI, and age correlate with diabetes risk?

- Which clinical variables contribute most to predicting diabetes?

- How accurate are the machine learning models used in predicting outcomes?

- What are the precision, recall, and F1-scores for the best-performing model?

- How does insulin concentration or blood pressure vary between diabetic and non-diabetic groups?
  

## 🧠 Skills and Concepts Demonstrated:

- Data Cleaning and Preprocessing (handling physiologically implausible values)

- Exploratory Data Analysis (EDA) using pandas, matplotlib, and seaborn

- Feature Engineering – imputing missing values using median replacement

- Supervised Learning with scikit-learn (Logistic Regression, Decision Tree, Random Forest)

- Model Evaluation – confusion matrix, accuracy, precision, recall, F1-score

- Data Visualization to reveal correlations and variable importance

- Binary Classification Techniques for medical diagnostics


## Data Visualization:

  <img width="813" height="658" alt="Screenshot 2025-10-18 131302" src="https://github.com/user-attachments/assets/0c90559f-ab13-4b56-99b3-c3215cc04152" />


## 📈 Analysis Interpretation:

_ Glucose level was the strongest predictor of diabetes presence — higher glucose readings consistently aligned with           positive outcomes (diabetic).

- BMI and age also exhibited meaningful relationships with diabetes risk, especially among older women.

- Replacing zero values in physiological columns (like Blood Pressure, BMI, Insulin) with median estimates improved data       integrity and model accuracy.

- Machine learning models achieved moderate to strong predictive performance, with Logistic Regression and Random Forest       performing best overall.

- Visualizations highlighted clear distinctions in glucose and BMI distributions between diabetic and non-diabetic             individuals.


## You can interact with the notebook here: 

https://colab.research.google.com/drive/1HmdO64azsNWz_-S-Zj1l1qF4M-BykmvQ?usp=sharing

## 🧩 Conclusions:

- Diabetes risk is strongly associated with glucose concentration, BMI, and age.

- Accurate data preprocessing (handling zeros and missing values) plays a crucial role in medical model reliability.

- Machine learning can serve as an effective screening tool for early diabetes detection.
  

## 💡 Recommendations:

- Collect broader demographic data (including male and non-Pima populations) to generalize findings.

- Test ensemble models like Gradient Boosting or XGBoost for performance improvement.

- Incorporate lifestyle variables such as physical activity and diet for deeper insights.

- Deploy predictive dashboards or web apps for healthcare practitioners to use as diagnostic support tools.

- Regularly retrain the model with updated patient data to maintain predictive accuracy.
