
# 💻 Laptop Price Prediction

This project builds a machine learning model to predict the prices of laptops based on their specifications using Python and Jupyter Notebook.

---

## 📁 Files Included

- `laptop_price.csv` – Dataset containing 1303 laptop records with technical specs
- `Laptop Price_Prediction.ipynb` – Jupyter notebook containing data analysis, preprocessing, and model training

---

## 🧠 Project Overview

- **Goal**: Predict `Price_euros` using features like CPU, RAM, GPU, Storage, etc.
- **Type**: Supervised Regression
- **Model(s)**: Includes at least one regression model (e.g., Linear Regression, Random Forest)

---

## 🔧 Steps Performed

1. **Data Cleaning**
   - Removed or transformed non-numeric entries (`RAM`, `Weight`, `Memory`)
   - Handled compound fields like `ScreenResolution`, `Cpu`, `Gpu`

2. **Exploratory Data Analysis**
   - Analyzed brand vs price, RAM vs price, SSD effect, etc.
   - Checked distributions and outliers

3. **Feature Engineering**
   - Categorical encoding
   - Feature extraction from string columns

4. **Modeling**
   - Built and evaluated regression models
   - Used metrics: RMSE, MAE, R²

---

## 📌 Requirements

Install the following Python libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## 🚀 How to Run

1. Open the `.ipynb` file in Jupyter or Google Colab
2. Run all cells from top to bottom
3. Review the model performance and visualizations

---

## 📈 Sample Results

- **Model Accuracy**: (e.g., R² = 0.87)
- **Best Features**: RAM size, SSD capacity, Brand, CPU type

---

## ✅ Next Steps (Optional)

- Convert notebook to script and add modular structure
- Deploy as web app using Streamlit
- Visualize in Power BI or Tableau

---

## 👤 Author
**Vamshi Krishna Reddy Attla**  
- 📧 vamshikrishna.reddy555@gmail.com  
- 🌐 [LinkedIn](https://www.linkedin.com/in/vamsikrishna11/)

