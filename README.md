# Classify_diabetes_dataset.py

# Logistic Regression on Simulated Diabetes Dataset

This project demonstrates a basic machine learning workflow using logistic regression to predict diabetes outcomes. It simulates a small version of the Pima Indians Diabetes dataset and uses logistic regression to classify whether a person is likely to have diabetes.

## 📁 Project Structure

```
├── diabetes_logistic_regression.py  # Main script
├── README.md                        # Project description
```

## 🧪 Dependencies

Ensure you have the following Python libraries installed:

* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn

Install them using pip if needed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 📊 Dataset

A manually created dataset mimicking the Pima Indians Diabetes dataset is used. It includes the following features:

* **Pregnancies**: Number of times pregnant
* **Glucose**: Plasma glucose concentration
* **BloodPressure**: Diastolic blood pressure (mm Hg)
* **SkinThickness**: Triceps skinfold thickness (mm)
* **Insulin**: 2-Hour serum insulin (mu U/ml)
* **BMI**: Body mass index (weight in kg/(height in m)^2)
* **DiabetesPedigreeFunction**: Diabetes pedigree function
* **Age**: Age in years
* **Outcome**: 0 = No diabetes, 1 = Diabetes

## 🚀 Workflow

1. **Data Initialization**: A small dataset is created and loaded into a pandas DataFrame.
2. **Exploratory Data Analysis**: A `pairplot` from Seaborn is used to visualize relationships among features.
3. **Data Preparation**: Features (`X`) and labels (`y`) are separated.
4. **Train-Test Split**: The dataset is split into training and testing sets.
5. **Model Training**: A logistic regression model is trained.
6. **Evaluation**:

   * Confusion Matrix
   * Accuracy Score
7. **Visualization**: The confusion matrix is plotted as a heatmap.

## 📈 Results

* Confusion matrix and accuracy are printed.
* A heatmap of the confusion matrix helps visualize model performance.

## 🧠 Sample Output

```
Confusion Matrix:
[[2 1]
 [1 0]]
Accuracy: 40.00%
```

*Note: Accuracy will vary depending on train-test split due to small dataset size.*

## 📌 Notes

* This is a basic example for educational purposes and uses a very small dataset.
* For real-world applications, use a larger, clean, and validated dataset.

