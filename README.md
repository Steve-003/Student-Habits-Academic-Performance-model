# Student Habits and Academic Performance


##  Project Overview
This project applies **statistical and machine learning techniques** to analyze how student habits, lifestyle choices, and demographic factors influence academic performance.  
The focus is not only on prediction accuracy, but also on **interpretability and insight generation** for education-related decision-making.

##  Objectives
- Predict student exam performance using behavioral and demographic variables  
- Explore relationships between study habits and academic outcomes  
- Compare regression-based models  
- Extract interpretable insights that can inform education policy and student support strategies  

##  Dataset Description
The dataset consists of student-level observations including:
- Study habits (e.g., study time)
- Lifestyle factors (e.g., sleep patterns, extracurricular activities)
- Demographic characteristics
- Academic performance (exam score – target variable)

The target variable is **continuous**, making the problem suitable for regression analysis.

##  Methodology

### 1. Data Preparation
- Missing value checks and handling  
- Data type validation  
- Encoding of categorical variables  
- Sanity checks on feature ranges  

### 2. Exploratory Data Analysis (EDA)
- Distribution analysis of numerical variables  
- Comparative analysis across categorical features  
- Correlation analysis and heatmaps  
- Identification of multicollinearity patterns  

### 3. Feature Engineering & Preprocessing
- Feature–target separation  
- Scaling where necessary  
- Train–test split for generalization evaluation  

### 4. Modeling
The project implements and compares multiple regression models, including:
- Baseline Linear Regression  
- Regularized regression techniques  

Models are evaluated using standard regression metrics to balance bias and variance.

##  Key Results
- Academic performance is more strongly associated with **study-related behaviors** than demographic attributes  
- Simple, interpretable models perform competitively  
- Feature importance aligns well with exploratory correlation analysis  

##  Insights
- Consistent study habits have a measurable positive impact on exam scores  
- Lifestyle variables matter, but their effects are nuanced  
- Interpretability is crucial for translating data science into actionable educational insights  

##  Limitations
- Cross-sectional data limits causal inference  
- Potential omitted variables (e.g., prior academic ability)  
- Results may not generalize across different educational systems  

##  Future Improvements
- Incorporate cross-validation for robustness  
- Add confidence intervals for model coefficients  
- Explore interaction effects between key habits  
- Improve reproducibility with:
  - Fixed random seeds
  - Modular project structure  

