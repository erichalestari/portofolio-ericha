# 👋 Hi, I’m Ericha Margareta Lestari

📍 Based in Lampung, Indonesia  
🎓 Actuarial Science Graduate | 📊 Data Enthusiast | 🧼 Local Business Owner  

---

## About Me

As a recent graduate in Actuarial Science from Institut Teknologi Sumatera (GPA 3.14, Class of 2025), I bring a solid foundation in insurance and financial principles, supported by practical data analysis skills in R, Python, and SQL. My academic journey included specialized coursework in Sharia Insurance, where I completed two major projects: a product review of BNI Life Hy-End Pro Syariah and a Tabarru’ fund estimation using Cost of Insurance (COI) modeling. These projects deepened my understanding of ethical risk-sharing, Islamic contract structures (akad), and actuarial applications in Sharia-compliant insurance.

During my internship at the Central Bureau of Statistics, I worked on export-import forecasting and survey data analysis using SPSS and Excel. I’m well-versed in data visualization tools like ggplot2 and Excel Charts, and have experience building automation tools with VBA and Pivot Tables to streamline workflows.

Beyond technical skills, I’ve demonstrated leadership through organizational roles and entrepreneurial experience, including planning and running business initiatives such as a healthy food startup and managing my current local laundry business. I am a communicative team player who learns quickly and adapts easily to new environments. With a blend of analytical thinking, business insight, and people skills, I’m excited to grow professionally and contribute to impactful, data-driven decisions—especially in the field of inclusive and ethical insurance.

---
### 🗂️ Table of Contents

- [📌 About Me](#about-me)
- [💼 Curriculum Vitae](#Curriculum-Vitae)
- [📊 Projects](#projects)
  - [ Python](#Python)
  - [ R](#R)
  - [Actuarial Application in Sharia Insurance](#actuarial-aplication-in-sharia-insurance)
- [📜 Certifications](#certifications)
- [🤝 Connect with Me](#connect-with-me)

---
## Curriculum Vitae 

A snapshot of my educational background, professional experience, projects, and skills—crafted to reflect my journey from actuarial science graduate to data analyst and entrepreneur.
📎 [View My CV](https://github.com/erichalestari/portofolio-ericha/blob/main/cv%20ericha.pdf)

---
## Project 

### Python 

## [Disaster Risk Profiling & Insurance Premium Estimation](https://github.com/erichalestari/global-risk-metrics/blob/main/Risk_Profiling_and_Insurance_Premium_Estimation.ipynb)

This project develops a data-driven framework for assessing regional disaster risk and estimating insurance premiums based on expected losses. Using historical disaster data, the notebook applies exploratory data analysis (EDA), risk scoring techniques, and premium modeling to support decision-making in disaster risk financing.

Objectives:
- Profile regional disaster risk based on frequency, severity, and exposure
- Estimate insurance premiums using expected loss and risk classification
- Visualize risk distribution and premium ranges across regions

Methodology Highlights:
- Data preprocessing and feature engineering from public disaster datasets
- Risk scoring using normalized metrics and weighted aggregation
- Premium estimation using actuarial principles and loss modeling
- Visual outputs including risk maps, score distributions, and premium tables

Key Insights:
- Regions with high disaster frequency and loss severity require differentiated premium strategies
- The model supports scalable integration with real-world insurance schemes
- Visualizations enhance interpretability for stakeholders and policymakers

Tools & Technologies: Python, Pandas, Matplotlib, Seaborn, Geopandas, Actuarial Modeling, Risk Scoring, Insurance Analytics

### R 

## [Forecasting Export Value of Lampung Province Using Double Exponential Smoothing Method (2018–2022)](https://github.com/erichalestari/portofolio-ericha/blob/main/Nilai%20Ekspor.pdf)
[Worksheet](https://github.com/erichalestari/portofolio-ericha/blob/main/exponential-smothing-inflasi.pdf)

This project focuses on forecasting the monthly export value of Lampung Province, Indonesia, using the Double Exponential Smoothing (DES) method. The study utilizes historical data from January 2018 to December 2022 obtained from the official website of the Central Bureau of Statistics (BPS). The goal is to identify export trends, generate short-term forecasts, and evaluate prediction accuracy.

Objectives:
- Analyze the data pattern of Lampung’s export values over five years
- Forecast export values for the upcoming five months (Jan–May 2023)
- Assess the accuracy of the DES model using MAPE and RMSE metrics

Methodology Highlights:
- Time series decomposition to identify trend components
- Application of Holt’s DES with optimized smoothing parameters (α = 0.461, β = 0.1)
- Accuracy evaluation using Mean Absolute Percentage Error (MAPE) and Root Mean Square Error (RMSE)

Key Findings:
- The export data exhibits a clear upward trend over time
- Forecasts indicate a gradual decline in export values from January to May 2023
- The DES model achieved a MAPE of 18.13% and RMSE of 83.35 million, categorized as “Good” accuracy

Tools & Technologies: R, Excel, Time Series Forecasting, Double Exponential Smoothing, Statistical Analysis, Data Visualization

## [Multiple Linear Regression Analysis: The Impact of Macroeconomic Factors on the Indonesian Rupiah Exchange Rate (Case Study: 2021–2023](https://github.com/erichalestari/portofolio-ericha/blob/main/Analisis%20Regresi%20Berganda.pdf)
[worksheet](https://github.com/erichalestari/portofolio-ericha/blob/main/anaregtubes.Rmd)

This project investigates the influence of five key macroeconomic variables—interest rate, inflation rate, money circulation, export value, and import value—on the exchange rate of the Indonesian Rupiah against the US Dollar using multiple linear regression analysis. The study covers data from 2021 to 2023 and includes classical assumption testing and parameter significance analysis.

Methodology Highlights:
- Data processing using Excel and RStudio
- Classical assumption tests: normality, autocorrelation, heteroscedasticity, multicollinearity
- Significance tests: F-test, T-test, and coefficient of determination (R²)

Key Findings:
- Interest rate, inflation rate, and export value have a statistically significant impact on the Rupiah exchange rate
- The regression model yields an Adjusted R² of 0.8515, indicating that 85.15% of the variation in exchange rate is explained by the independent variables

Tools & Technologies: R, Excel, Statistical Modeling, Data Visualization, Econometrics

## [Pure Premium Rate Estimation for Earthquake Insurance Using Generalized Linear Models (GLM)](https://github.com/erichalestari/portofolio-ericha/blob/main/Penentuan%20Premi%20Dengan%20GLM.pdf)
[worksheet](https://github.com/erichalestari/portofolio-ericha/blob/main/Penentua%20Premi%20GLM.pdf)

This project develops a statistical model to estimate pure premium rates for earthquake insurance using Generalized Linear Models (GLM). The analysis is based on real-world data from an Indonesian insurance company covering the period January 2018 to September 2023. The goal is to identify significant predictors of claim size and frequency, and to construct a reliable premium estimation model.

Objectives:
- Model earthquake insurance claim size using Gamma-distributed GLM
- Model claim frequency using Negative Binomial-distributed GLM
- Estimate pure premium rates by combining expected claim size and frequency

Methodology Highlights:
- Predictor variables include occupancy zone, cause of loss, commission, and insured value
- Multicollinearity and significance tests conducted to refine model inputs
- Goodness-of-fit and R² metrics used to validate model performance
- Final premium model integrates both GLMs to simulate company revenue and premium differentiation

Key Findings:
- Occupancy zone, cause of loss, and insured value significantly affect claim size
- Occupancy zone is the most influential factor in claim frequency
- The combined model yields an Adjusted R² of 0.905 for claim size and 0.704 for claim frequency
- Premium rates vary significantly across occupancy zones, supporting risk-based pricing strategies

Tools & Technologies: R, GLM, Gamma & Negative Binomial Distribution, Actuarial Modeling, Insurance Analytics, Statistical Inference

### Actuarial Aplication in Sharia Insurance 

## [Analytical Review of Unit-Linked Sharia Insurance Product](https://github.com/erichalestari/portofolio-ericha/blob/main/ASURANSI%20SYARIAH.pdf)

An in-depth evaluation of BNI Life Hy-End Pro Syariah, focusing on:
- Contract Structures: Wakalah bil Ujrah, Tabarru’, Mudharabah Musytarakah
- Benefits & Risk Management: Life protection, Sharia-compliant investment handling, and claim payments from the tabarru’ fund
- Fee Analysis: Breakdown of acquisition, administration, surrender, and cooling-off charges
- Sharia Compliance Assessment: Review of product alignment with risk-sharing and non-riba principles

## [Estimating Tabarru’ Fund in Sharia Life Insurance](https://github.com/erichalestari/portofolio-ericha/blob/main/Asuransi%20Syariah%20Kelompok%206.pptx)

This is a group project I worked on to estimate the Tabarru’ Fund in a Sharia-based life insurance product. We used the Cost of Insurance (COI) method and looked at how interest rates and loading factors affect the amount participants need to pay.

Purpose & Method
- Goal: To calculate the Tabarru’ Fund using mortality data from the Indonesian Mortality Table (TMI IV) and BI interest rates from 2018–2022.
- Tools: We used EasyFit and Microsoft Excel for simulations.
- Case Study: Two participants (male and female), both aged 40, with 5-year term insurance and a death benefit of Rp200 million.

Key Results
- Higher loading factors lead to higher COI and Tabarru’ Fund values.
- Male participants pay more than females due to higher mortality risk.
- Higher interest rates reduce the COI and Tabarru’ Fund.
- The Tabarru’ Fund increases each year during the protection period.

This project helped me understand how interest rates and management costs play a big role in Sharia insurance calculations. It also showed how actuarial methods can support fair and transparent fund management based on Islamic principles.


---
## Certifications

- [IBM – Introduction to Data Analysis](https://coursera.org/verify/OEPNCS41KIDL)  
- [TOEFL – ITERA Language Center](https://drive.google.com/file/d/12h5fApL3PW1gVkvkn3CfU8pISbgzTYg2/view?usp=sharing)  
- [IBM – Data Classification & Summarization](https://www.credly.com/badges/e849f03f-f5aa-433-996d-8c2dd242dad1/public_url)

---

## 🤝 Connect with Me

📧 erichamargaretalestari@gmail.com  
🌐 [LinkedIn](https://www.linkedin.com/in/erichalestari)
