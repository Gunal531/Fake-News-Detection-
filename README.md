# Fake-News-Detection-

### 📰 Fake News Detection Using TF-IDF and Logistic Regression
This project predicts Real vs Fake News using TF-IDF vectorization and Logistic Regression with analysis and visualizations using Pandas, Seaborn, and Matplotlib.

## 🚀 How It Works
### 1️⃣ Load Dataset: Import news articles dataset containing text and labels (REAL / FAKE).

### 2️⃣ Data Cleaning & Preparation:

Extract text as features (X) and label as target (y).

Encode labels: REAL = 1, FAKE = 0.

### 3️⃣ Train-Test Split:

Split data into 80% training and 20% testing using train_test_split.

### 4️⃣ TF-IDF Vectorization:

Convert text into numerical vectors using TF-IDF, emphasizing important words while ignoring common words.

### 5️⃣ Model Building:

Train a Logistic Regression model using the vectorized data.

### 6️⃣ Evaluation:

Calculate accuracy, precision, recall, and F1-score using classification_report.

Visualize confusion matrix for clarity on predictions.

### 7️⃣ Visualization:

Plot label distribution and text length distribution using Seaborn.

Display confusion matrix for model evaluation.

Plot top 20 TF-IDF terms correlated with Real News for interpretability.

## 🛠️ Libraries Used
Pandas for data handling

Seaborn & Matplotlib for visualization

Scikit-learn for:

Train-test splitting

TF-IDF vectorization

Logistic Regression modeling

Evaluation metrics


## Visualization
Label distribution using sns.countplot.

Text length distribution using sns.histplot.

Confusion matrix using sns.heatmap.

Top TF-IDF terms indicating Real News using sns.barplot.

### 🎯 Results
✅ Achieved high accuracy (~91%) on test data.
✅ Balanced prediction of Real vs Fake News.
✅ Clear insights on which words contribute to Real News prediction.

### 🌟 Future Improvements
✅ Use advanced models (Random Forest, XGBoost, LSTM) for comparison.
✅ Add Streamlit app for interactive fake news detection.
✅ Perform hyperparameter tuning for improved accuracy.
✅ Incorporate word clouds for intuitive feature visualization.

🤝 Contribution
Feel free to fork, raise issues, or contribute improvements to enhance the project.
