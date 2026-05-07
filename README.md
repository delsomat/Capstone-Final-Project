Predicting Supply Chain Disruptions and Recovery Times Using Machine Learning

A machine learning and data analytics project focused on predicting supply chain recovery times and identifying the major operational, logistical, and financial factors that contribute to disruption severity and business downtime. This project uses exploratory data analysis (EDA), feature engineering, Principal Component Analysis (PCA), and Random Forest Regression to analyze 100,000 simulated supply chain disruption events across multiple industries.

📌 Project Overview

Modern supply chains are highly interconnected, making them vulnerable to disruptions such as:

Cyberattacks
Natural disasters
Labor strikes
Geopolitical conflicts
Port congestion
Factory incidents

The goal of this project was to build a predictive analytics framework capable of estimating full recovery time after a disruption while identifying the variables that most strongly influence operational recovery.

🎯 Objectives
Predict supply chain recovery duration using machine learning
Identify key variables that impact disruption recovery time
Analyze operational and financial consequences of disruptions
Evaluate the usefulness of machine learning for supply chain risk management
Provide business insights for improving resilience and mitigation planning
📊 Dataset Information
Source: Kaggle Supply Chain Disruption and Recovery Dataset
Records: 100,000 disruption events
Industries Included:
Automotive
Electronics
Pharmaceuticals
Consumer Goods
Aerospace
Key Variables
Variable	Description
full_recovery_days	Target variable representing total recovery duration
disruption_severity	Severity score of disruption
production_impact_pct	Production capacity reduction percentage
revenue_loss_usd	Financial loss caused by disruption
response_time_days	Time required to respond to disruption
supplier_tier	Supplier dependency level
has_backup_supplier	Availability of backup supplier
response_type	Mitigation strategy used

🛠️ Technologies Used
Programming & Environment
Python
Jupyter Notebook
Libraries
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
Machine Learning Techniques
Random Forest Regressor
Principal Component Analysis (PCA)
Feature Engineering
StandardScaler
Label Encoding
One-Hot Encoding
🔍 Exploratory Data Analysis (EDA)

The project included extensive exploratory data analysis to uncover patterns and relationships within the data.

Analysis Performed
Correlation heatmaps
Distribution histograms
Scatterplots
Boxplots
Outlier analysis
Bivariate and multivariate analysis
Major Findings
Higher disruption severity strongly correlates with longer recovery times
Revenue loss increases significantly with production impact
Cyberattacks and geopolitical disruptions produced the most unpredictable recovery durations
Tier 1 supplier disruptions caused the highest operational and financial impact
Backup suppliers improved supply chain resilience
🤖 Machine Learning Model
Model Used

Random Forest Regressor

The model was selected because it:

Handles nonlinear relationships effectively
Performs well on structured business datasets
Provides feature importance analysis
Supports high-dimensional data
Evaluation Metrics
Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)
R² Score
📈 Principal Component Analysis (PCA)

PCA was applied to reduce dimensionality and analyze feature relationships.

PCA Results
PC1 explained 12.13% of dataset variance
16 principal components explained approximately 80% of total variance
Recovery outcomes depend on multiple interacting variables rather than a single factor
Key PCA Insights
PC1 represented disruption intensity
PC2 reflected supplier resilience and backup supplier availability
PC3 captured geographic supplier structure
💡 Business Insights

This project demonstrates how predictive analytics can help organizations:

Improve disruption response planning
Strengthen supplier diversification strategies
Reduce operational downtime
Minimize financial losses
Build more resilient supply chains

The findings show that machine learning can provide meaningful support for supply chain risk management and operational decision-making.

📷 Visualizations Included

The project contains multiple visualizations, including:

Correlation heatmaps
Recovery time boxplots
Production impact histograms
Revenue loss scatterplots
PCA scree plots
Supplier severity comparisons
🚀 Future Improvements

Appendix

<img width="1006" height="1028" alt="image" src="https://github.com/user-attachments/assets/ca60c153-3b38-48b3-b42d-4d8acacdf9d7" />
Figure 1: Supplier Tier, Disruption Severity, Production Impact Outliers Boxplots

<img width="998" height="1370" alt="image" src="https://github.com/user-attachments/assets/01e72d42-3f4c-46ae-aa81-e518c6b626ee" />
Figure 2: Revenue Loss, Response Time, Partial/Full Recovery Days Outliers Boxplots 

<img width="1736" height="938" alt="image" src="https://github.com/user-attachments/assets/de372fae-9e77-4b52-a556-f9b5db28d9a4" />
Figure 3: Distribution of Production Impact Percentage Histogram

<img width="2036" height="1188" alt="image" src="https://github.com/user-attachments/assets/732e5020-944e-4aa6-915e-5daedc03e16c" />
Figure 4: Full Recovery Days by Disruption Type Boxplots 

<img width="1766" height="1022" alt="image" src="https://github.com/user-attachments/assets/faa43f29-effd-4321-afb3-44fd9bfefa0a" />
Figure 5: Proportion of Disruption Severity by Supplier Size Bar Chart 

<img width="1758" height="1076" alt="image" src="https://github.com/user-attachments/assets/50f39a62-4dc2-41db-9a61-c21121d500d0" />
Figure 6: Revenue Loss vs Production Impact Scatterplot 

<img width="1718" height="1288" alt="image" src="https://github.com/user-attachments/assets/ae0dd783-7bbf-4b48-9a48-50c57981365a" />
Figure 7: Correlation Heatmap of Numerical Variables   

<img width="1024" height="646" alt="image" src="https://github.com/user-attachments/assets/1d2ceebe-2a51-4cec-b02d-9a2571f4497c" />
Figure 8: Scree plot for PCA and the cumulative explained variance 

Potential future enhancements include:

Testing advanced models such as XGBoost or Neural Networks
Incorporating real-time supply chain data
Building an interactive Power BI dashboard
Expanding geographic and industry coverage
Adding time-series forecasting capabilities
📚 References
Kaggle Supply Chain Disruption and Recovery Dataset
Komorowski et al. (2016) — Exploratory Data Analysis
👨‍💻 Authors
Carter Williams
Matthew Del Sol
Urooj Ali

Kean University — Integrative Data Analytics
May 2026
