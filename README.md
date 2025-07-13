# SCT_TrackCode_3
Decision Tree Classifier – Bank Marketing Dataset

This project builds a Decision Tree Classifier to predict whether a customer will subscribe to a term deposit based on their demographic and behavioral data using the Bank Marketing Dataset from the UCI Machine Learning Repository.


---

📌 Project Overview

Objective: Predict if a customer will purchase a product or service (term deposit) based on features such as age, job, marital status, education, contact communication type, previous marketing outcomes, etc.

Algorithm Used: Decision Tree Classifier (scikit-learn)

Dataset: Bank Marketing Data Set from UCI (bank.csv)



---

🔧 Steps Performed

1. Imported necessary libraries – pandas, sklearn, matplotlib.
2. Loaded dataset into a pandas DataFrame
3. Encoded categorical variables using Label Encoding.
4. Split dataset into features and target (y).
5. Performed train-test split (70% train, 30% test).
6. Built Decision Tree Classifier and trained it on training data.
7. Predicted outcomes on the test data.
   
8. Evaluated model performance using:
Accuracy Score
Classification Report
Confusion Matrix


9. Visualized the Decision Tree using matplotlib.

---

📊 Results

The model provides insights into which features contribute most to the prediction of term deposit subscription.

Achieved an accuracy (based on test data) printed in the output after running the code.



---

🗃️ Files

bank.csv – Dataset file (uploaded via Colab Files tab).

decision_tree_bank_marketing.ipynb – Main Colab notebook containing:

Data preprocessing

Model training

Evaluation

Visualization code


▶️ How to Run

1. Upload bank.csv in Google Colab.


2. Run the combined code cell in the notebook.


3. View printed evaluation metrics and decision tree visualization.


4. Modify hyperparameters such as max_depth to see changes in tree complexity and performance.


---

📌 Key Libraries Used

pandas

scikit-learn

matplotlib


---

💡 Future Scope

Implement Random Forest Classifier for improved accuracy.

Perform hyperparameter tuning using GridSearchCV.

Explore feature importance plots for business insights.


---

👩‍💻 Author

Akshaya
M.Sc Applied Data Science
SRM Institute of Science and Technology
