# PaisaBazaar Banking Fraud Analysis

**Exploratory Data Analysis (EDA) of the Paisabazaar Banking Fraud dataset**

This project performs an in-depth Exploratory Data Analysis of customer demographics, financial attributes, and repayment behaviours to uncover patterns, correlations, and risk clusters relevant for:

- Fraud detection  
- Credit risk assessment  
- Customer segmentation  

---

## 📂 Dataset

- **Source**: Policy Bazaar Dataset  
- **Original link**: [https://github.com/crushervp/PaisaBazaar-Banking-Fraud-Analysis](https://github.com/crushervp/PaisaBazaar-Banking-Fraud-Analysis/blob/main/dataset_compressed.csv)  
- **Size**: ~30 MB  
- **Download method**: via `github` (no manual download needed)

```python
# Load dataset directly from GitHub
url = "https://github.com/crushervp/PaisaBazaar-Banking-Fraud-Analysis/raw/main/dataset_compressed.csv"
df = pd.read_csv(url)
```
## ⚙️ How to Run

- Clone the repository

```bash
git clone https://github.com/crushervp/PaisaBazaar-Banking-Fraud-Analysis.git
cd PaisaBazaar-Banking-Fraud-Analysis
```

- Install dependencies
```
# Recommended: use a virtual environment
python -m venv venv
source venv/bin/activate    # Linux / macOS
venv\Scripts\activate       # Windows

pip install -r requirements.txt
```

- Open and run the notebook
  - Preferred: open PaisaBazaar_Fraud_EDA.ipynb in Google Colab or Jupyter Lab / VS Code

  - The dataset will be automatically downloaded via kagglehub when you run the first cells
 
## 📊 Key Insights

| Area             | Main Findings     |
|:-----------------|:------------------|
| Numeric Correlations        | Outstanding Debt, EMI, Debt-to-Income ratio → strong indicators of repayment stress       |
| Demographics           | Clear Age vs. Income progression → useful for customer segmentation           |
| Categorical Behaviour    | Occupation × Credit Mix × Payment Behaviour → distinct risk clusters       |
| Repayment Delays    | Delay categories act as early warning signals for future defaults       |

## ✅ Business Impact

- Strengthened fraud detection and credit scoring models
- Better design of tailored loan products aligned with real customer repayment capacity
- More effective targeted interventions for high-risk customer clusters
- Improved recovery rates through proactive monitoring and early action

## 📌 Conclusion
This EDA provides a solid foundation for data-driven decision-making in financial services.
By combining numeric correlations with behavioural and demographic insights, organizations can:

- Reduce fraud exposure
- Improve loan recovery rates
- Enhance overall customer satisfaction

→ ultimately driving more sustainable and profitable growth in the lending business.
