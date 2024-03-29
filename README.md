CREDIT CARD FRAUD ANOMALY DETECTION



OVERVIEW
Welcome to my Credit Card Fraud Anomaly Detection project! This project is one of my initial ventures into the field of data science. The goal is to identify fraudulent transactions among credit card transactions made by European cardholders in September 2013. The dataset is highly unbalanced, with frauds accounting for only 0.172% of all transactions.

DATASET:

The dataset contains transactions over two days, totaling 284,807 transactions, with 492 frauds. Unfortunately, due to confidentiality issues, the original features and background information about the data cannot be provided. The features 'V1' through 'V28' are principal components obtained with PCA, while 'Time' and 'Amount' are the only features not transformed. 'Time' represents the seconds elapsed between each transaction and the first transaction in the dataset, and 'Amount' is the transaction amount. The 'Class' feature is the response variable, taking the value 1 in case of fraud and 0 otherwise.


Methodology

1. Data Preprocessing
Exploratory Data Analysis (EDA) to understand the distribution and characteristics of the dataset.
Handling imbalanced data using the Interquartile Range (IQR) method.
Scaling and standardizing numerical features.

2. Anomaly Detection Techniques
Unsupervised Learning: Utilized anomaly detection algorithms such as Isolation Forest, Local Outlier Factor (LOF), and One-Class SVM to identify unusual patterns in the data.
Supervised Learning: Employed various machine learning algorithms like Random Forest, Support Vector Machines (SVM), and Gradient Boosting for fraud detection.

Results and Findings
Evaluated model performance using metrics like precision, recall, and F1-score.
Visualized results and decision boundaries for better interpretation.
Analyzed feature importance to understand the contributing factors in fraud detection.

How to Use
Clone the repository to your local machine.
Install the required dependencies mentioned in the requirements.txt file.
Open and run the Jupyter Notebooks or Python scripts to explore the analysis and results.


DISCLAIMER:

This project is for educational and analytical purposes only. It does not endorse any specific financial or security practices.

Contributions and feedback are welcome! If you have suggestions, improvements, or want to add new features, feel free to fork the repository and submit a pull request.
