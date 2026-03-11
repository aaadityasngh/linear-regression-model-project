# 📈 Linear Regression Model Project

A hands-on machine learning project demonstrating **Simple** and **Multiple Linear Regression** using Python and scikit-learn. This project walks through the complete ML workflow — from data exploration and preprocessing to model training, evaluation, and prediction.

---

## 🚀 Features

- **Simple Linear Regression** — Predict height from weight using a single feature
- **Multiple Linear Regression** — Predict California housing prices using 8 features
- Comprehensive **Exploratory Data Analysis (EDA)** with visualizations
- Feature scaling with **StandardScaler**
- Model evaluation using **MSE, MAE, RMSE, R², and Adjusted R²**
- Residual analysis and regression **assumption checks**
- Model persistence using **pickle**

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Python 3** | Core language |
| **Jupyter Notebook** | Interactive development |
| **pandas** | Data manipulation |
| **NumPy** | Numerical computing |
| **Matplotlib** | Plotting and visualization |
| **Seaborn** | Statistical visualizations |
| **scikit-learn** | ML models, metrics, preprocessing |
| **pickle** | Model serialization |

---

## 📁 Project Structure

```
linear-regression-model-project/
├── 3.0-Simple+Linear+Regression.ipynb   # Simple linear regression notebook
├── 4.0-Multiple+Linear+Regression.ipynb # Multiple linear regression notebook
├── height-weight.csv                    # Dataset for simple regression
└── README.md
```

---

## 📊 Datasets

### 1. Height–Weight Dataset (`height-weight.csv`)

A small dataset with **22 samples** mapping body weight (kg) to height (cm).

| Feature | Description | Range |
|---------|-------------|-------|
| Weight | Body weight in kg | 45–105 |
| Height | Body height in cm | 120–183 |

### 2. California Housing Dataset (built-in)

The scikit-learn California Housing dataset with **20,640 samples** and **8 features** including median income, house age, average rooms, population, and more. The target variable is the **median house value**.

---

## ⚙️ Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/aaadityasngh/linear-regression-model-project.git
   cd linear-regression-model-project
   ```

2. **Create a virtual environment (recommended)**

   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

4. **Launch Jupyter Notebook**

   ```bash
   jupyter notebook
   ```

---

## 📓 Notebooks

### Notebook 1 — Simple Linear Regression

**File:** `3.0-Simple+Linear+Regression.ipynb`

Covers the fundamentals of linear regression with a single independent variable:

1. Load and visualize the height–weight dataset
2. Split data into training and testing sets (80/20)
3. Apply feature scaling with `StandardScaler`
4. Train a `LinearRegression` model
5. Evaluate with MSE, MAE, RMSE, R², and Adjusted R²
6. Perform residual analysis and assumption checks
7. Make predictions (e.g., predict height for weight = 80 kg)

### Notebook 2 — Multiple Linear Regression

**File:** `4.0-Multiple+Linear+Regression.ipynb`

Extends regression to multiple features using the California Housing dataset:

1. Load dataset and perform EDA (statistics, null checks, correlations)
2. Visualize feature relationships with a correlation heatmap
3. Split data into training and testing sets (67/33)
4. Scale features with `StandardScaler`
5. Train a `LinearRegression` model on 8 features
6. Evaluate with MSE, MAE, RMSE, R², and Adjusted R²
7. Visualize actual vs predicted values and residual distributions
8. Save the trained model using `pickle`

---

## 📏 Evaluation Metrics

| Metric | Formula | What It Measures |
|--------|---------|------------------|
| **MSE** | Mean Squared Error | Average of squared prediction errors |
| **MAE** | Mean Absolute Error | Average of absolute prediction errors |
| **RMSE** | √MSE | Error in original units |
| **R²** | Coefficient of Determination | Proportion of variance explained (0–1) |
| **Adjusted R²** | R² adjusted for number of features | Penalizes adding irrelevant features |

---

## ▶️ Usage

Open either notebook in Jupyter and run all cells sequentially:

```bash
jupyter notebook "3.0-Simple+Linear+Regression.ipynb"
```

Or for the multiple regression example:

```bash
jupyter notebook "4.0-Multiple+Linear+Regression.ipynb"
```

Each notebook is self-contained — just run the cells from top to bottom and follow the inline explanations.

---

## 🤝 Contributing

Contributions are welcome! If you'd like to improve this project:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## 📄 License

This project is open source and available for educational purposes.

---

> **Built with ❤️ for learning Machine Learning fundamentals.**
