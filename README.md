# 🌟 Texas Salary Prediction Model

This project utilizes machine learning techniques to predict salaries within the state of Texas based on key features in a given dataset. The goal is to develop an accurate and robust regression model that can provide meaningful insights into salary determinants.

---

## 🔬 Methodology and Models

The analysis is performed within a Jupyter/Colab Notebook (`texasSalPred (1).ipynb`) and follows a standard data science workflow:

1. **Data Loading and Cleaning**  
   - Handle missing values  
   - Verify and correct data types  
   - Prepare raw data for analysis  

2. **Exploratory Data Analysis (EDA)**  
   - Visualize salary distributions  
   - Analyze correlations between independent variables (job title, experience, education, etc.) and salary  

3. **Feature Engineering**  
   - Encode categorical variables  
   - Scale numerical features  

4. **Model Training & Evaluation**  
   Multiple regression algorithms are trained and compared, including:  
   - Linear Regression  
   - Random Forest Regressor (or similar ensemble method)  
   - *(Add any other models used)*  

---

## 📊 Results and Evaluation

Model performance is evaluated using standard regression metrics:

- **Mean Squared Error (MSE):** Measures the average squared difference between predictions and actual values.  
- **R-squared (R²):** Indicates the proportion of variance in the dependent variable explained by independent variables.  

The notebook also includes **visual comparisons (bar charts)** to highlight the best-performing algorithm for salary prediction.

---

## 🛠️ Technologies Used

- **Python 3**  
- **pandas** – Data manipulation  
- **numpy** – Numerical operations  
- **scikit-learn** – Machine learning models and tools  
- **matplotlib & seaborn** – Data visualization  
- **Jupyter / Google Colab** – Notebook environment  

---

## 📂 Repository Structure

├── texasSalPred (1).ipynb # Main notebook with analysis & models
├── data/ # Dataset
├── README.md # Project documentation

