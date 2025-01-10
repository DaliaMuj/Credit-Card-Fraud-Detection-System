<!DOCTYPE html>
<html lang="en">
<body>
    <h1>Credit Card Fraud Detection System</h1>
    <p>
        This <strong>Credit Card Fraud Detection System</strong> was developed as part of my bachelor's degree project. The primary objective of this system is to detect fraudulent transactions using machine learning techniques. It combines theoretical knowledge with practical application, showcasing a comprehensive approach to solving real-world financial fraud challenges.
    </p>

  <h2>🌟 Key Features</h2>
    <ul>
        <li>Integrated <strong>two datasets</strong> for robust and diversified analysis.</li>
        <li>Performed advanced <strong>data preprocessing</strong>, including handling missing values, checking for duplicate values, and analyzing dataset shape and columns.</li>
        <li>Conducted exploratory data analysis with <strong>visualizations</strong> to uncover patterns and trends in the data.</li>
        <li>Identified the <strong>most important features</strong> using the <code>SelectKBest</code> method.</li>
        <li>Built and evaluated five machine learning models:
            <ul>
                <li>Logistic Regression</li>
                <li>Random Forest Classifier</li>
                <li>Linear Support Vector Classifier</li>
                <li>XGBoost</li>
                <li>Feedforward Neural Network (FFNN)</li>
            </ul>
        </li>
        <li>Evaluated model performance using a <strong>confusion matrix</strong>, <strong>classification report</strong>, and <strong>F1 Macro Score</strong>, effectively addressing class imbalance.</li>
    </ul>

  <h2>🛠️ Technologies and Tools</h2>
    <ul>
        <li><strong>Programming Language</strong>: Python</li>
        <li><strong>Data Manipulation</strong>: pandas, numPy</li>
        <li><strong>Machine Learning</strong>: scikit-learn, xgboost, imbalanced-learn, pytorch</li>
        <li><strong>Visualization</strong>: plotly</li>
        <li><strong>Development Environment</strong>: Jupyter Notebook</li>
    </ul>

  <h2>📊 Datasets</h2>

   <h3>Dataset 1: <a href="https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud">Link</a></h3>
    <ul>
        <li><strong>Description:</strong> Transactions made by European credit cardholders over two days. Out of 284,807 transactions, only 492 are fraudulent, making this dataset highly imbalanced.</li>
        <li><strong>Features:</strong>
            <ul>
                <li>30 columns, with 28 anonymized features (e.g., <code>V1</code>, <code>V2</code>, ..., <code>V28</code>).</li>
                <li><code>Time</code>: Seconds elapsed between this transaction and the first transaction in the dataset.</li>
                <li><code>Amount</code>: Transaction amount, which can help as a feature for identifying fraud.</li>
                <li>Target column: <code>Class</code> (1 = Fraud, 0 = Legitimate).</li>
            </ul>
        </li>
        <li><strong>Class Distribution:</strong>
            <ul>
                <li>Legitimate: 99.83%</li>
                <li>Fraudulent: 0.17%</li>
            </ul>
        </li>
    </ul>

   <h3>Dataset 2: <a href="https://www.kaggle.com/datasets/dhanushnarayananr/credit-card-fraud">Link</a></h3>
    <ul>
        <li><strong>Description:</strong> Records of credit card activities to support fraud detection efforts.</li>
        <li><strong>Features:</strong>
            <ul>
                <li>Attributes such as <code>Transaction_ID</code>, <code>Date</code>, <code>Amount</code>, and <code>Merchant</code>.</li>
                <li>Target column: <code>Is_Fraud</code> (1 = Fraud, 0 = Legitimate).</li>
            </ul>
        </li>
      <li><strong>Class Distribution:</strong>
            <ul>
                <li>Legitimate: 91.3%</li>
                <li>Fraudulent: 8.74%</li>
            </ul>
        </li>
    </ul>

  <h2>🧠 Methodology</h2>
    <ol>
        <li><strong>Data Preprocessing:</strong> Minimal cleaning was required. Used <code>SMOTE</code> to address class imbalance.</li>
        <li><strong>Exploratory Data Analysis (EDA):</strong> Visualized data trends using <strong>plotly</strong>.</li>
        <li><strong>Feature Selection:</strong> Applied <code>SelectKBest</code> to identify the most important features.</li>
        <li><strong>Model Development:</strong> Built and tuned models using <code>GridSearchCV</code> and <code>Stratified K-Fold</code> validation.</li>
        <li><strong>Model Evaluation:</strong> Used a confusion matrix and classification report, focusing on F1 Macro Score.</li>
    </ol>
    <h2>🏆 Results</h2>
    <ul>
        <li><strong>Best Model:</strong> Random Forest Classifier</li>
        <li><strong>Dataset 1:</strong></li>
        <ul>
          <li><strong>Precision:</strong> 90.8%</li>
          <li><strong>Recall:</strong> 89.6%</li>
          <li><strong>F1-macro score:</strong> 90.2%</li>
        </ul>
        <li><strong>Dataset 2:</strong></li>
        <ul>
          <li><strong>Precision:</strong> 90.8%</li>
          <li><strong>Recall:</strong> 89.6%</li>
          <li><strong>F1-macro score:</strong> 90.2%</li>
    </ul>
    <h2>💭 Final Thoughts</h2>
    <p>
        This project exemplifies the power of machine learning in addressing critical challenges like fraud detection. It highlights a holistic approach, from handling class imbalance to building robust models. Through this project, I honed my skills in data preprocessing, feature selection, model evaluation, and visualization, while gaining deeper insights into the financial domain.
    </p>
    <p>
        The success of this project encourages further exploration into advanced techniques, including deploying the system in real-world scenarios to provide proactive fraud detection solutions.
    </p>
</body>
</html>
