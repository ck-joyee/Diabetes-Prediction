# 🩺 Diabetes Prediction using Support Vector Machine (SVM)

A machine learning project that predicts whether a patient is **diabetic or non-diabetic** based on diagnostic health measurements. Built using a **Support Vector Machine (SVM)** classifier with a linear kernel, this project also includes a live predictive system that takes patient input and returns an instant diagnosis prediction.

---

## 📊 Dataset

- **Source:** Pima Indians Diabetes Dataset
- **Features:** 8 diagnostic measurements including glucose level, blood pressure, BMI, insulin, age, and more
- **Target:** Outcome — Diabetic (1) or Non-Diabetic (0)

---

## 🧠 Model

| Model | Kernel |
|---|---|
| Support Vector Machine (SVM) | Linear |

SVM was chosen for its effectiveness on small-to-medium sized medical datasets with clear class boundaries.

---

## ⚙️ Workflow

1. **Data Loading & Exploration** — checked shape, class distribution, and group means
2. **Preprocessing** — separated features and labels, applied StandardScaler for feature standardisation
3. **Train/Test Split** — 80/20 split with stratification to preserve class balance
4. **Model Training** — trained SVM classifier on training data
5. **Evaluation** — measured accuracy on both training and test sets
6. **Predictive System** — built a real-time input system that takes 8 health measurements and predicts diabetic status

---

## 🛠️ Tech Stack

- Python 3
- Pandas, NumPy
- Scikit-learn (SVM, StandardScaler, train_test_split)
- Jupyter Notebook

---

## 🚀 How to Run

```bash
# 1. Clone the repo
git clone https://github.com/ck-joyee/Diabetes-Prediction.git
cd Diabetes-Prediction

# 2. Install dependencies
pip install numpy pandas scikit-learn

# 3. Launch the notebook
jupyter notebook Diabetes_Prediction.ipynb
```

---

## 🔮 Predictive System

The notebook includes a working predictive system. Input 8 health measurements and the model returns:

```
Input:  (Pregnancies, Glucose, BloodPressure, SkinThickness,
         Insulin, BMI, DiabetesPedigreeFunction, Age)

Example: (3, 158, 76, 36, 245, 31.6, 0.851, 28)
Output:  "The person is diabetic"
```

---

## 📁 Project Structure

```
Diabetes-Prediction/
│
├── data/
│   └── diabetes.csv            # Dataset
├── Diabetes_Prediction.ipynb   # Main notebook
└── README.md
```

---

## 👩‍💻 Author

**Joyee Chakraborty**
Master of Information Technology — Central Queensland University, Brisbane
🔗 [LinkedIn](https://www.linkedin.com/in/joyee-chakraborty) | [Portfolio](https://joyee-ck.netlify.app/) | [Related Publication](https://wseas.com/index.php/cr/article/view/6)
