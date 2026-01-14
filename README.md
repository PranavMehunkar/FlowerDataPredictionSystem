<h1>Flower Data Prediction System</h1>
Flower Data Prediction System is a machine learning project that predicts the species of an Iris flower based on its physical measurements. The goal is to analyze factors and build a reliable prediction system using supervised learning techniques.

<h2>Project Structure</h2>
<ul><li>iris_data.ipynb – Model for training and evaluation</li></ul>
<ul><li>Iris.csv – Dataset used for training and evaluation</li></ul>

<h2>Models Used</h2>
The following models were trained and evaluated:<br>
<ul><li>Logistic Regression</li></ul>
<ul><li>K-Nearest Neighbors (KNN)</li></ul>
<ul><li>Naive Bayes</li></ul>
Model performance was compared using accuracy, precision, recall, F1-score, and confusion matrix.

<h2>Model Comparison</h2>
<table>
<tr><th>Model</th><th>Accuracy (%)</th></tr>
<tr><td>Logistic Regression</td>	<td>100.0</td></tr>
<tr><td>K-Nearest Neighbors</td>	<td>99.93</td></tr>
<tr><td>Naive Bayes</td>	<td>99.93</td></tr>
</table>
<b>“Logistic Regression achieved higher accuracy, making it useful in various scenarios.”</b>

<h2>Final Model Selection</h2>
Based on comparative evaluation across multiple metrics, <b>Logistic Regression</b> demonstrated the most consistent performance and was selected as the final model.

<h2>Technologies Used</h2>
<ul><li>Pandas, NumPy</li></ul>
<ul><li>Scikit-learn</li></ul>
<ul><li>Jupyter Lab</li></ul>

<h2>Future Work</h2>
<ul><li>Deploy the final model using Streamlit</li></ul>
<ul><li>Improve feature engineering</li></ul>
<ul><li>Add model interpretability and UI enhancements</li></ul>

<h2>Key Learnings</h2>
During this project, I learned and applied several important machine learning and data preprocessing concepts, including:
<ul><li>Building a machine learning based classification system that can automatically predict the species of an Iris flower based on its physical measurements</li></ul>
<ul><li>Encoding categorical variables using <b>LabelEncoder</b> based on feature type</li></ul>
<ul><li>Building classification models using Logistic Regression, K-Nearest Neighbors (KNN) and Naive Bayes</li></ul>
<ul><li>Training all three models, compare their performances, and identify the best algorithm</li></ul>
