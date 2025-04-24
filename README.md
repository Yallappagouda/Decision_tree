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

[Screenshot 2025-04-24 230632](https://github.com/user-attachments/assets/9e0508ec-83c7-47f7-8383-16010aa589ba)





🚀 Future Scope
Add support for Random Forest

Turn into a Jupyter Notebook for interactive demos

Build a web interface using Streamlit or Flask


