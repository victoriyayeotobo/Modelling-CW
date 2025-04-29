# Income Classification and Fairness Analysis Using Machine Learning

This project explored building income classification models while tackling real-world challenges like data imbalance, fairness issues, and computational cost.  
It was a major step in applying machine learning thoughtfully — not just chasing accuracy, but ensuring ethical and practical outcomes.

---

## Objective

To classify individuals into income groups based on demographic and employment-related features, while:
- Handling class imbalance to prevent bias
- Ensuring fairness across demographic groups
- Evaluating computational efficiency for practical deployment

---

## My Learning Focus

- **Data Preprocessing**:  
  Learned how to transform LIBSVM-format datasets into structured formats, handle missing values, and scale features appropriately.

- **Handling Class Imbalance**:  
  Applied **SMOTE**, **Random Undersampling**, and **SMOTE-ENN** to create balanced training sets — and compared their impact on model fairness and performance.

- **Fairness Evaluation**:  
  Analyzed **false positive rates** and **false negative rates** across demographic groups to detect and measure model bias.

- **Model Development**:  
  Built and compared six different models — Logistic Regression, SVM, Random Forest, Naïve Bayes, Neural Networks (MLP), and Gaussian Process Classifier.

- **Hyperparameter Tuning**:  
  Used GridSearchCV to optimize Random Forest and SVM models.

- **Ethical Considerations**:  
  Reflected on how bias, transparency, and privacy must be handled when machine learning impacts real human decisions like income classification.

---

## Tools and Libraries

- Python
- scikit-learn
- imbalanced-learn
- pandas, NumPy
- matplotlib, seaborn

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/victoriyayeotobo/Modelling-CW.git
   cd Modelling-CW
   
2. Install the dependencies:
  pip install -r requirements.txt

3. Run the notebook:
  Open Modelling_CW.ipynb in Jupyter Notebook or Google Colab.

Note:
This project pushed me to think beyond model performance, by emphasizing fairness, real-world applicability, and the social impact of machine learning solutions.
