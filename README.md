# Customer Churn Prediction for Banking Industry

## 🏦 Project Overview
This project develops a machine learning solution to predict customer churn for Beta Bank, helping the institution proactively identify customers likely to leave and implement retention strategies. The model focuses on achieving high precision and recall balance through the F1-score metric.

## 📊 Business Problem
Beta Bank faces a critical challenge: customers are gradually leaving each month, and acquiring new customers is significantly more expensive than retaining existing ones. The bank needs a predictive model to:

- **Identify at-risk customers** before they leave
- **Optimize retention efforts** by focusing resources on customers most likely to churn
- **Reduce customer acquisition costs** by improving retention rates
- **Increase overall profitability** through better customer lifecycle management

## 🎯 Project Objectives
- **Primary Goal**: Develop a classification model with F1-score ≥ 0.59
- **Secondary Goals**: 
  - Compare AUC-ROC performance with F1-score
  - Handle class imbalance effectively using multiple techniques
  - Provide actionable insights for business strategy

## 📈 Dataset Features
The dataset contains **customer behavioral data and contract termination history** with the following attributes:

### Customer Demographics:
- **Geography**: Country of residence
- **Gender**: Customer gender
- **Age**: Customer age
- **Surname**: Customer surname

### Banking Relationship:
- **CreditScore**: Credit rating value
- **Tenure**: Duration of fixed deposit maturity (years)
- **Balance**: Current account balance
- **NumOfProducts**: Number of bank products used
- **HasCrCard**: Credit card ownership (1=Yes, 0=No)
- **IsActiveMember**: Customer activity status (1=Active, 0=Inactive)
- **EstimatedSalary**: Estimated annual income

### Target Variable:
- **Exited**: Customer churn indicator (1=Left, 0=Stayed)

## 🔬 Technical Approach

### 1. **Data Preprocessing & Analysis**
- Comprehensive data exploration and quality assessment
- Feature engineering and selection
- Class distribution analysis and visualization

### 2. **Class Imbalance Handling**
Implementation of multiple techniques to address dataset imbalance:
- **Resampling methods** (Oversampling/Undersampling)
- **Algorithmic approaches** (Class weights, ensemble methods)
- **Synthetic data generation** (SMOTE, ADASYN)

### 3. **Model Development & Evaluation**
- **Multiple algorithm comparison**: Logistic Regression, Random Forest, Gradient Boosting
- **Hyperparameter optimization** using cross-validation
- **Performance evaluation**: F1-score, AUC-ROC, Precision, Recall
- **Model interpretability** for business insights

## 🛠️ Technologies & Libraries
- **Python 3.x**
- **pandas** & **numpy** - Data manipulation and analysis
- **scikit-learn** - Machine learning algorithms and metrics
- **matplotlib** & **seaborn** - Data visualization
- **imbalanced-learn** - Class imbalance handling techniques
- **Jupyter Notebook** - Interactive development environment

## 📋 Project Structure
```
├── notebook.ipynb              # Main analysis and modeling notebook
├── README.md                   # Project documentation
├── data/
│   └── Churn.csv              # Customer churn dataset
└── results/
    ├── model_performance.png   # Performance comparison charts
    └── feature_importance.png  # Feature analysis visualizations
```

## 🚀 How to Run
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/customer-churn-prediction.git
   cd customer-churn-prediction
   ```

2. **Install required dependencies**:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn imbalanced-learn jupyter
   ```

3. **Open and run the notebook**:
   ```bash
   jupyter notebook notebook.ipynb
   ```

## 📊 Key Results & Impact
- **Model Performance**: Achieved F1-score > 0.59 threshold
- **Business Value**: Enables proactive customer retention strategies
- **Technical Achievement**: Successfully handled class imbalance using multiple approaches
- **Actionable Insights**: Identified key factors contributing to customer churn

## 📈 Model Performance Metrics
- **F1-Score**: [Your achieved score] (Target: ≥ 0.59)
- **AUC-ROC**: [Your achieved score]
- **Precision**: [Your achieved score]
- **Recall**: [Your achieved score]

## 🎯 Business Applications
This model can be integrated into Beta Bank's CRM system to:
- **Trigger retention campaigns** for high-risk customers
- **Personalize offers** based on churn probability
- **Optimize marketing budget** allocation
- **Monitor customer satisfaction** trends

## 🔍 Key Insights Discovered
- [Add your main findings about which features are most predictive of churn]
- [Include insights about customer segments most at risk]
- [Mention any surprising discoveries from your analysis]

## 🤝 Contributing
Feel free to fork this project and submit pull requests for any improvements.

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
*This project demonstrates end-to-end machine learning workflow for a real-world business problem, including data preprocessing, class imbalance handling, model selection, and performance evaluation with business impact consideration.*