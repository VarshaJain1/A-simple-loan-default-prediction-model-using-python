# A-simple-loan-default-prediction-model-using-python
This project builds a loan default prediction model using synthetic data inspired by SBI’s FY2025 Annual Report.

 Data Source
- SBI Annual Report FY2025
- Key Credit Risk Metrics:
- Gross NPA Ratio: 1.82%
- Net NPA Ratio: 0.47%
- Sector-wise Advances & NPAs (Agriculture, Industry, Services, Personal Loans)

 Methodology
1. Generated synthetic loan-level dataset using SBI’s sector-wise NPA ratios.
2. Simulated borrower attributes (income, credit score, loan amount, tenure).
3. Built a Logistic Regression model to classify defaults.
4. Evaluated using ROC-AUC and classification metrics.

Tech Stack
- Python (pandas, numpy, scikit-learn)
- Jupyter Notebook (EDA + Modelling)

Future Enhancements
- Try advanced ML models (Random Forest, XGBoost).
- Link model outputs to **Expected Credit Loss (ECL)** and **Basel capital requirements**.
- Extend with open banking datasets.

Conclusion  
This project demonstrates how publicly available information, such as SBI’s annual report, can be leveraged to simulate loan-level data and build predictive credit risk models.  
By aligning sector-level NPA ratios with synthetic borrower attributes, we created a simplified but realistic dataset to train a machine learning model for loan default prediction. While the dataset is not actual loan-level data, it captures the essence of SBI’s portfolio risk distribution and shows how risk managers and analysts can transform financial disclosures into actionable risk models.  
This repository serves as a foundation that can be extended with advanced models, stress testing, or integration with regulatory frameworks like **Basel III/IV**. It highlights how financial reports can bridge academic learning with practical risk management applications.  
