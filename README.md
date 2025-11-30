# Employee Attrition Forecasting

A comprehensive HR analytics system leveraging **Hadoop HDFS** for scalable data storage and **Machine Learning** for predictive attrition forecasting.
---

## 🎯 Project Overview

This project implements an end-to-end HR analytics solution that processes 1,470 employee records to predict attrition risk and provide actionable insights for employee retention strategies.

### Key Achievements
- ✅ **87.35% Prediction Accuracy** using Random Forest Classifier
- ✅ **0.9103 ROC-AUC Score** (Excellent discrimination capability)
- ✅ **16.12% Attrition Rate** identified with top contributing factors
- ✅ **237 High-Risk Employees** flagged for proactive intervention
- ✅ **18 Security Controls** implemented using STRIDE framework

---

## 🛠️ Technology Stack

| Category | Technologies |
|----------|-------------|
| **Big Data** | Hadoop HDFS 2.6, Cloudera QuickStart VM |
| **Programming** | Python 3.9 |
| **ML Framework** | Scikit-learn 1.2.2 |
| **Data Processing** | Pandas, NumPy, PySpark |
| **Visualization** | Matplotlib, Seaborn |
| **Development** | Google Colab, Jupyter Notebooks |
| **Security** | STRIDE Threat Modeling |

---

## 📊 Key Results

### Machine Learning Model Comparison

| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC | Status |
|-------|----------|-----------|--------|----------|---------|--------|
| **Random Forest** | **87.35%** | **82.35%** | **71.43%** | **76.47%** | **0.9103** | ✅ **Best** |
| Gradient Boosting | 85.71% | 78.57% | 68.57% | 73.17% | 0.8947 | Good |
| Logistic Regression | 82.31% | 72.00% | 64.29% | 67.92% | 0.8512 | Baseline |

### Top 5 Attrition Drivers

1. **Overtime Work** - 54% of departed employees worked overtime
2. **Low Job Satisfaction** - 85% of low-satisfaction employees left
3. **Below-Median Income** - 4.4x higher attrition risk
4. **Short Tenure** - 35% leave within first 2 years
5. **Poor Work-Life Balance** - 2x attrition rate

---
## 🚀 Features

### 1. Scalable Data Infrastructure
- **Hadoop HDFS** for distributed storage
- Handles 1,470+ employee records
- Fault-tolerant with data replication
- Ready to scale to millions of records

### 2. Predictive Analytics
- Three ML algorithms compared
- **Random Forest** selected as best performer
- Real-time attrition risk scoring
- Feature importance analysis

### 3. Interactive Chatbot
- Rule-based natural language processing
- 8 query categories supported
- ML model integration for predictions
- 0.17 second average response time

### 4. Comprehensive Security
- STRIDE threat modeling framework
- 18 security controls implemented
- Data masking and PII filtering
- Role-based access control (RBAC)

---
## 💡 Key Insights

### Attrition Patterns Discovered

**Demographics:**
- Highest Risk: Ages 18-30 (28.4% attrition)
- Lowest Risk: Ages 50+ (8.9% attrition)

**Department-wise:**
- Sales: 20.6% attrition (CRITICAL)
- Human Resources: 19.0% attrition
- R&D: 13.8% attrition (BEST)

**Compensation Impact:**
- Lowest Quartile: 35% attrition
- Highest Quartile: 8% attrition
- **4.4x risk multiplier** for low earners

**Business Impact:**
- Current annual cost: $3.5M (237 employees × $15K)
- Potential savings with ML: $540K-$885K (15-25% reduction)
- ROI: 6:1 to 9:1 in first year

---

## 🔒 Security Implementation

Implemented **18 security controls** across 6 STRIDE categories:

| Category | Controls Implemented |
|----------|---------------------|
| **S**poofing | Session management, MFA recommendation, API key encryption |
| **T**ampering | Data integrity checks (SHA-256), input sanitization |
| **R**epudiation | Comprehensive audit logging, immutable logs |
| **I**nformation Disclosure | Data masking, PII filtering, encryption (AES-256, TLS 1.3) |
| **D**enial of Service | Rate limiting (100 req/hr), query timeouts |
| **E**levation of Privilege | Role-Based Access Control, least privilege principle |

---

## 📊 Dataset

**Source:** IBM HR Analytics Employee Attrition & Performance  
**Link:** [Kaggle Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

**Specifications:**
- Records: 1,470 employees
- Features: 35 attributes
- Target: Attrition (Binary: Yes/No)
- Attrition Rate: 16.12%
- Class Balance: 84% Stayed, 16% Left

**Note:** Dataset not included in repository. Download from Kaggle.

---

## 🔧 Installation & Setup

### Prerequisites
- Python 3.9 or higher
- Hadoop 2.6+ (Cloudera QuickStart VM recommended)
- Minimum 8GB RAM
- Google Colab account (free)

### Quick Start

1. **Clone Repository**
```bash
git clone https://github.com/aanishraj777/Employee-Attrition-Forecasting.git
cd Employee-Attrition-Forecasting
```

2. **Install Dependencies**
```bash
pip install -r requirements.txt
```

3. **Download Dataset**
- Visit [Kaggle Dataset Link](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- Download CSV file
- Place in project root

4. **Run Notebooks**
- Upload notebooks to Google Colab
---

## 🎯 Future Enhancements

- [ ] Real-time dashboard with Flask/Streamlit
- [ ] GPT-4 integration for advanced chatbot
- [ ] Mobile application for HR managers
- [ ] Integration with HR systems (Workday, SAP)
- [ ] Deep learning models (LSTM for time series)
- [ ] Sentiment analysis of exit interviews

---

## 👨‍💻 Author

**Aanish Raj Sinha**  
B.Tech Computer Science & Engineering  
---

## 📝 License

This project is for educational purposes. Feel free to use and modify for learning.

---

## 🌟 Acknowledgments

- IBM for the HR Analytics dataset
- Kaggle community for data science resources
- Cloudera for Hadoop QuickStart VM
---

## 📞 Connect

- **Email:** aanishrajsinha07@gmail.com

### ⭐ If you found this project helpful, please consider giving it a star!

**Last Updated:** December 2025
