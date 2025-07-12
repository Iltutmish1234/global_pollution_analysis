# 🌍global_pollution_analysis
📌<b> Objective:</b>
<br>This project analyzes global pollution data and predicts energy recovery potential from pollution levels using machine learning. Both Linear Regression and Logistic Regression models are applied to understand and classify pollution patterns and their impact on energy recovery strategies.

🔄 <b>Project Workflow:</b>
 <br>📊<b>Phase 1: Data Collection & Exploratory Data Analysis (EDA)</b>
 <br>Dataset: Global_Pollution_Analysis.csv<br>
 
<b>Data Preprocessing:</b>
 <br>Handled missing values with appropriate imputation. <br>
Encoded categorical features (Country, Year). <br>
Normalized pollution indices (air, water, soil).

<b>EDA:</b>
 <br>Descriptive stats of CO₂ emissions, waste, etc. <br>
Correlation analysis with energy metrics using heatmaps. <br>
Trend visualizations (bar charts, line plots, boxplots).

🧠 <b>Phase 2: Predictive Modeling</b>
 <br>📈 <b>Linear Regression</b>
 <br>Objective: Predict energy recovery (in GWh) using pollution-related features. <br>
Features: Air Pollution Index, CO₂ Emissions, Industrial Waste, etc. <br>

<b>Evaluation Metrics:</b>
 <br>R² Score <br>
Mean Squared Error (MSE) <br>
Mean Absolute Error (MAE)

🔢<b> Logistic Regression</b>
 <br>Objective: Classify countries into pollution categories: Low, Medium, High. <br>
 
<b>Evaluation Metrics:</b>
 <br>Accuracy <br>
Precision, Recall, F1-score <br>
Confusion Matrix

📊 <b>Phase 3: Reporting & Insights</b>
 <br>Compared performance of both regression models. <br>
Visualized model outputs with confusion matrices and classification reports. <br>
Identified trends across years and regions. <br>

<b>Extracted key insights:</b>
 <br>Pollution levels strongly correlate with industrial waste and emissions. <br>
Countries with higher pollution can benefit from improved energy recovery programs. <br>

🛠️ <b>Tech Stack:</b>
<br>Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)<br>
Jupyter Notebook<br>
Machine Learning (Linear & Logistic Regression)

✅ <b>Conclusion:</b>
<br>This project shows how pollution data can be used to both classify environmental severity and estimate potential energy recovery. The results can guide policymakers and researchers in crafting sustainable and efficient pollution control strategies.
