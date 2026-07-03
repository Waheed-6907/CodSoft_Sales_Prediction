# 📈 Sales Prediction Using Python

Predicting product sales using **Machine Learning** based on advertising expenditure across **TV, Radio, and Newspaper** platforms. This project demonstrates the complete machine learning workflow, including data exploration, visualization, model training, evaluation, and prediction using **Linear Regression**.

---

## 📌 Project Overview

Sales prediction helps businesses estimate future sales by analyzing historical advertising data. By understanding how different advertising channels influence sales, companies can make informed marketing decisions and optimize their advertising budget.

This project follows a complete Data Science pipeline:
- 📂 Data Loading
- 🔍 Exploratory Data Analysis (EDA)
- 📊 Data Visualization
- 🤖 Model Training
- 📈 Performance Evaluation
- 🎯 Sales Prediction

---

## 🛠️ Technologies Used

- 🐍 Python
- 🐼 Pandas
- 🔢 NumPy
- 📊 Matplotlib
- 🎨 Seaborn
- 🤖 Scikit-learn

---

## 📁 Dataset

The dataset contains advertising budgets and corresponding sales values.

| Feature | Description |
|---------|-------------|
| 📺 TV | TV Advertising Budget |
| 📻 Radio | Radio Advertising Budget |
| 📰 Newspaper | Newspaper Advertising Budget |
| 💰 Sales | Product Sales |

---

## ⚙️ Machine Learning Workflow

### 1️⃣ Import Libraries
Import all required Python libraries.

### 2️⃣ Load Dataset
Read the dataset using Pandas.

### 3️⃣ Exploratory Data Analysis (EDA)
- Dataset Information
- Missing Values
- Statistical Summary
- Duplicate Check

### 4️⃣ Data Visualization
- 📊 Histograms
- 🔥 Correlation Heatmap
- 📈 Pair Plot
- 📉 Scatter Plots

### 5️⃣ Feature Selection
- Independent Variables (TV, Radio, Newspaper)
- Dependent Variable (Sales)

### 6️⃣ Train-Test Split
Split data into:
- ✅ 80% Training
- ✅ 20% Testing

### 7️⃣ Model Training
Train a **Linear Regression** model.

### 8️⃣ Prediction
Predict sales on unseen data.

### 9️⃣ Model Evaluation
Evaluate performance using:

- 📌 Mean Absolute Error (MAE)
- 📌 Mean Squared Error (MSE)
- 📌 R² Score

### 🔟 Visualization
Compare **Actual vs Predicted Sales** using scatter plots.

---

## 📊 Results

| Metric | Value |
|---------|--------|
| ✅ MAE | **1.24** |
| ✅ MSE | **2.76** |
| ✅ R² Score | **0.91** |

### 📌 Interpretation

- 📺 **TV Advertising** has the strongest influence on sales.
- 📻 **Radio Advertising** has a moderate impact.
- 📰 **Newspaper Advertising** has the least impact.
- 🎯 The model explains approximately **91%** of the variation in sales, indicating excellent predictive performance.

---

## 📷 Visualizations

This project includes:

- 📊 Histograms
- 🔥 Correlation Heatmap
- 📈 Pair Plot
- 🎯 Actual vs Predicted Sales Plot

---

## 📂 Project Structure

```
Sales-Prediction-Using-Python/
│
├── Advertising.csv
├── Sales_Prediction.ipynb
├── requirements.txt
├── README.md
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/Waheed-6907/CodSoft_Sales_Prediction.git
```

Move into the project directory:

```bash
cd Sales-Prediction-Using-Python
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the Jupyter Notebook:

```bash
jupyter notebook
```

---

## 🎯 Future Improvements

- 🌳 Random Forest Regression
- 🚀 XGBoost Regression
- 🧠 Neural Networks
- 📊 Interactive Dashboard using Streamlit
- 🌐 Web Deployment

---

## 🤝 Contributing

Contributions are welcome!

If you'd like to improve this project, feel free to fork the repository and submit a pull request.

---

## 📄 License

This project is licensed under the **MIT License**.

---

## ⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub!

---
---

<div align="center">

### 👨‍💻 Made with ❤️ by **Waheed Mujtaba**

</div>

<div align="center">

### 💻 Made with ❤️ using Python & Machine Learning

**Happy Coding! 🚀**

</div>
