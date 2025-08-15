# -Student-Score-Prediction
📊 Student Performance Prediction

This project applies Machine Learning regression techniques to predict student exam performance based on various factors such as study hours, sleep, and other academic/lifestyle features.

🚀 Project Overview
The project includes two models:
Linear Regression (Baseline Model)
Provides a simple linear fit between input features and exam scores.
Acts as a benchmark for evaluating more complex models.
Polynomial Regression (Extended Model)
Captures non-linear relationships between student factors and exam performance.
Allows testing the effect of different polynomial degrees on model accuracy.
📂 Project Files
linear_regression.ipynb → Jupyter Notebook with the linear regression model.
polynomial_regression.ipynb → Notebook with polynomial regression implementation.
StudentPerformanceFactors.csv → Dataset used for training/testing.
🛠️ Steps Performed
Data Cleaning & Preprocessing
Handling missing values and duplicates.
Feature selection and scaling.
Model Training
Splitting dataset into training and testing sets.
Applying Linear & Polynomial Regression.
Evaluation Metrics
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
R² Score
Visualization
Actual vs Predicted scores plotted for model performance.
📈 Results
Linear Regression served as a simple baseline.
Polynomial Regression showed better fit at certain degrees but risked overfitting at higher degrees.
🔑 Key Learning
Linear regression is a strong baseline but may not capture complex patterns.
Polynomial regression improves flexibility but requires careful degree selection.
Proper evaluation and visualization are critical for model comparison.
👨‍💻 How to Run
Clone the repository:
git clone https://github.com/MustafaBasit521/-Student-Score-Prediction.git
Open the notebooks in Google Colab or Jupyter Notebook.
Upload the dataset (StudentPerformanceFactors.csv) when prompted.
Run all cells to reproduce results.
