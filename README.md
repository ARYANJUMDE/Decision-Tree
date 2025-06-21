# Decision-Tree
# 🎯 Titanic Survival Prediction - Decision Tree Classifier

This project uses the Titanic dataset to predict whether a passenger survived or not using a Decision Tree Classifier from scikit-learn.

---

## 📌 About the Dataset

The dataset includes features such as:
- **Sex**
- **Age**
- **Fare**
- **PassengerId** *(included for now, can be dropped to improve model)*

The target variable is:
- `Survived`: 1 (Yes), 0 (No)

---

## ⚙️ Technologies Used

- Python 🐍
- Pandas
- scikit-learn
- Matplotlib (for tree visualization)

---

## 🧠 ML Model

### Algorithm:
- **Decision Tree Classifier**  
- Criterion: `'entropy'`  
- You can control complexity using:
  - `min_samples_split`
  - `max_leaf_nodes`
# 🎯 Titanic Survival Prediction - Decision Tree Classifier

This project uses the Titanic dataset to predict whether a passenger survived or not using a Decision Tree Classifier from scikit-learn.

---

## 📌 About the Dataset

The dataset includes features such as:
- **Sex**
- **Age**
- **Fare**
- **PassengerId** *(included for now, can be dropped to improve model)*

The target variable is:
- `Survived`: 1 (Yes), 0 (No)

---

## ⚙️ Technologies Used

- Python 🐍
- Pandas
- scikit-learn
- Matplotlib (for tree visualization)

---

## 🧠 ML Model

### Algorithm:
- **Decision Tree Classifier**  
- Criterion: `'entropy'`  
- You can control complexity using:
  - `max_depth`
  - `min_samples_split`
  - `max_leaf_nodes`

---

## 📊 Workflow

1. Data Cleaning:
   - Dropped columns like `Name`, `Cabin`, `Ticket`, etc.
   - Handled missing values in `Age`.

2. Feature Encoding:
   - Converted `Sex` column to numeric (`male` → 0, `female` → 1)

3. Model Training:
   - Split data into training and testing sets.
   - Fitted a Decision Tree classifier.

4. Visualization:
   - Plotted the decision tree using `plot_tree()` from `sklearn.tree`.

---

---

## 📊 Workflow

1. Data Cleaning:
   - Dropped columns like `Name`, `Cabin`, `Ticket`, etc.
   - Handled missing values in `Age`.

2. Feature Encoding:
   - Converted `Sex` column to numeric (`male` → 0, `female` → 1)

3. Model Training:
   - Split data into training and testing sets.
   - Fitted a Decision Tree classifier.

4. Visualization:
   - Plotted the decision tree using `plot_tree()` from `sklearn.tree`.

