🧠 Credify: Predicting Credit Card Approvals with Logistic Regression

This project builds a machine learning model to predict whether a credit card application will be approved or denied, using logistic regression and hyperparameter tuning with cross-validation.

My project uses a Credit Approval dataset from UCI's Machine Learning Repository (https://archive.ics.uci.edu/) and demonstrates the full workflow - from data preprocessing to model evaluation with ROC curves and confusion matrices.

📊 Project Overview

Financial institutions often receive thousands of credit card applications. Automating the decision process helps reduce manual effort and improve consistency. Credify leverages Logistic Regression, a supervised classification model, to predict approvals or denials based on applicant features.

⚙️ Technologies Used

Python 3.10+

NumPy

Pandas

Matplotlib

scikit-learn


📈 Model Evaluation
ROC Curve
<img width="780" height="459" alt="Screenshot 2025-11-10 at 7 01 19 PM" src="https://github.com/user-attachments/assets/3cb1dd8f-4dc5-4456-8499-08fe8d2452cf" />
The model’s ROC curve shows strong separation between classes 
with high AUC, indicating good discrimination ability.

Confusion Matrix
<img width="84" height="44" alt="Screenshot 2025-11-10 at 7 02 49 PM" src="https://github.com/user-attachments/assets/212289af-5f11-4672-8f16-fb0bbea86b39" />

✅ Interpretation:
The model achieves 81% accuracy, with balanced precision and recall, effectively predicting both approved and denied cases.

🚀 Results

Best training CV score: 0.832

Test accuracy: 0.807

Conclusion: Logistic regression with tuned hyperparameters performs robustly on the credit approval dataset, balancing bias and variance effectively.

🧠 Future Improvements

Experiment with other classifiers (Random Forest, XGBoost)

Feature importance visualization

Handle class imbalance (if present)

Deploy model as a web API for real-time credit decisions


👤 Author

Benjamin Yang
University of North Carolina at Chapel Hill
📧 bbyang@unc.edu

🔗 GitHub: BenYang12
