# FraudGuard-ML 💳🔒
Welcome to FraudGuard-ML, a cutting-edge machine learning project designed to detect credit card fraud with precision and flair! 🎯 Built by a team of passionate developers from Ulster University, this project leverages data science to secure financial transactions and boost trust in the digital economy. 💸

Project Overview 📋
    What’s the Deal? 🤔
    FraudGuard-ML uses the Kaggle Credit Card Fraud Detection dataset (284,807 transactions!) to identify fraudulent activities in real-time. With only 0.172% of transactions being fraud, we tackled the class imbalance head-on using advanced ML techniques. 🎉
    Tech Stack: 🛠️
        Python 🐍
        Libraries: Pandas, Scikit-learn, XGBoost, Seaborn, Matplotlib, Imbalanced-learn
        Tools: Google Colab, Kaggle API
    Key Features: 🌟
        Data cleaning and preprocessing (no missing values, duplicates gone! ✅)
        Feature engineering with PCA and Random Forest for top-notch insights 📊
        Models: Logistic Regression, Random Forest, SVM, and XGBoost (winner with 0.94 AUC-PR! 🏆)
        Real-time fraud detection simulation 🎮
        Stunning visualizations (heatmaps, violin plots, scatter plots) 📈

How It Works ⚙️
Data Import & Cleaning: 📥
    Grabbed the dataset from Kaggle, cleaned it with Pandas, and sampled 10,000 records for efficiency. No dirty data here! 🧹
    Data Wrangling: 🔧
    Scaled features like Time and Amount with StandardScaler, balanced classes with SMOTE. Balanced datasets = happy models! ⚖️
    Analysis & Visualization: 📊
    Plotted class distributions, correlation heatmaps, and feature distributions to uncover fraud patterns. Eye-candy for data lovers! 👀
    Modeling: 🤖
    Trained multiple classifiers, with XGBoost shining brightest (F1-Score: 0.86, AUC-PR: 0.94). Confusion matrices? Check! ROC curves? Double check! 📉
    Deployment: 🚀
    Built a real-time prediction function and saved the Random Forest model for deployment. Ready to catch fraudsters in action! 🕵️‍♂️

Results & Impact 🌍

    Performance: 📈
    XGBoost nailed it with a 93.6% probability on a sample transaction (Transaction ID: 172001, Amount: €149.23). False positives? Minimized! 💪
    Impact: 💡
    With global card fraud losses hitting $32.34 billion in 2022, FraudGuard-ML is a step toward safer online banking. Let’s protect those wallets! 🛡️
    Limitations: ⚠️
    Class imbalance, feature interpretability (thanks, PCA!), and overfitting risks are noted. Future work: fairness audits and real-world testing! 🔍
