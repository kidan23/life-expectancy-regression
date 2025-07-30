
# 🌍 Life Expectancy Prediction Using Machine Learning

This project uses various regression algorithms to predict **life expectancy** based on multiple socio-economic and health-related features. 


 📊 Dataset

- Source: [Kaggle - Life Expectancy Data](https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who)
- Rows: ~2,900
- Columns: 22
- Includes variables such as:
  - Adult Mortality
  - Alcohol consumption
  - BMI
  - Schooling
  - GDP
  - Income composition of resources
  - Status (Developed/Developing), etc.

---

 ⚙️ Models Used

- Linear Regression
- Random Forest Regressor
- Support Vector Regressor (SVR)
- Gradient Boosting Regressor

Each model was trained and evaluated using:
- RMSE (Root Mean Square Error)
- MAE (Mean Absolute Error)
- R² Score

---

📌 Features

- Data cleaning (missing values, infinities)
- Feature encoding and scaling
- Model training and evaluation
- Visualizations:
  - Actual vs Predicted scatter plots
  - Metric comparison bar chart
  - Correlation heatmap
  - Pairplot of selected features
  - Histograms of data distribution

---

 📁 Project Structure

```

├── life\_expectancy\_model.ipynb   # Main analysis code
├── README.md                     # Project description
└── Life Expectancy Data.csv      # Dataset (from Kaggle)

---

---

🧪 How to Run

1. **Download the dataset** from [this Kaggle link](https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who).
2. Place the CSV in the working directory.
3. Run the notebook or Python file in your preferred environment (Jupyter, VSCode, Colab, etc.).

---

## 🛠 Requirements

Install the following Python libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
````

---

## 📈 Sample Output

The best-performing model is typically the **Random Forest Regressor**, providing higher R² and lower RMSE compared to other models.

![Example Plot](https://upload.wikimedia.org/wikipedia/commons/thumb/1/1a/Regression_line_example.svg/600px-Regression_line_example.svg.png)

---

## 🙋‍♂️ Author

* GitHub: https://github.com/kidan23
* Project by an aspiring data scientist passionate about real-world ML applications.

---

## 📄 License

This project is for educational purposes. Dataset is available publicly on Kaggle under their terms of use.

