# 🌸 BlossomTree: Decision Tree Classifier on Iris Dataset

This project implements a **Decision Tree classifier** on the classic **Iris dataset** using **Scikit-learn**. The model is trained and evaluated on petal and sepal measurements to classify different Iris flower species.

---

## 💡 Dataset

We use the built-in `load_iris()` dataset from Scikit-learn, which includes 150 samples of 3 different Iris species:
- Setosa
- Versicolor
- Virginica

Each sample has 4 features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

---

## 🛠️ Steps Involved

1. Load the Iris dataset
2. Explore and inspect the data
3. Split into training and test sets
4. Train a Decision Tree Classifier
5. Evaluate the model using accuracy and classification report
6. Visualize the decision tree using matplotlib

---

## 📁 Project Structure + Setup

decision-tree-iris/

├── decision_tree_iris.py       
├── README.md                     
└── requirements.txt    


### 🔧 Setup Instructions

Install all dependencies and run the project with the following commands:

```bash
# Clone the repository
git clone https://github.com/yourusername/BlossomTree.git
cd BlossomTree

# Install required packages
pip install -r requirements.txt

# Run the script
python decision_tree_iris.py


📦 Requirements
These packages are used in the project (already listed in requirements.txt):
pandas
numpy
matplotlib
scikit-learn

✅ Output
You will see:

Accuracy score and classification report in the terminal

A plotted decision tree displayed via matplotlib

🌳 Visualization Example
![Screenshot 2025-04-24 230632](https://github.com/user-attachments/assets/c552ef89-1e99-48e1-804c-24b10ad01e4d)
Features:
    sepal length (cm)  sepal width (cm)  petal length (cm)  petal width (cm)
0                5.1               3.5                1.4               0.2
1                4.9               3.0                1.4               0.2
2                4.7               3.2                1.3               0.2
3                4.6               3.1                1.5               0.2
4                5.0               3.6                1.4               0.2

Target:
 0    0
1    0
2    0
3    0
4    0
dtype: int64

Accuracy: 1.0

Classification Report:
               precision    recall  f1-score   support

           0       1.00      1.00      1.00        10
           1       1.00      1.00      1.00         9
           2       1.00      1.00      1.00        11

    accuracy                           1.00        30
   macro avg       1.00      1.00      1.00        30
weighted avg       1.00      1.00      1.00        30









🚀 Future Scope
Add support for Random Forest

Turn into a Jupyter Notebook for interactive demos

Build a web interface using Streamlit or Flask


