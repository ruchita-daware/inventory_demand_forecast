# Inventory Demand Forecast

This project aims to predict future inventory demand using historical sales data. By leveraging machine learning models, it helps businesses optimize stock levels, minimize overstock and stockouts, and improve inventory planning.

## 🚀 Features

- Data preprocessing and cleaning
- Demand forecasting using ML models:
  - Linear Regression
  - Lasso Regression
  - XGBoost
- Model evaluation (MAE, RMSE, R²)
- Visualization of actual vs. predicted demand

## 📁 Project Structure

```

inventory-demand-forecast/
│
├── data/                # Raw and processed datasets
├── notebooks/           # Jupyter notebooks for EDA and modeling
├── models/              # Trained model files (optional)
├── src/                 # Source code for preprocessing and training
├── results/             # Forecast results and visualizations
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation

````

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/inventory-demand-forecast.git
   cd inventory-demand-forecast
````

2. Create a virtual environment and activate it:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## 🧠 Model Training

Run the training script or Jupyter notebook to preprocess the data and train models.

```bash
python src/train_model.py
```

## 📊 Results

Model performance is evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R-squared Score (R²)

Visualizations show how well the models forecast future inventory demand.

## 📝 License

This project is licensed under the [MIT License](LICENSE).

## 🤝 Contributions

Contributions, issues, and feature requests are welcome! Feel free to open a pull request.
