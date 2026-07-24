# Karachi Air Pollution Prediction

## Project Title
**Predictive Analysis System for Karachi Air Quality**

## Objective
This project aims to analyze air quality data collected from Aga Khan University, Karachi, and develop machine learning models to predict PM2.5 levels based on environmental and sensor data. The goal is to provide valuable insights into pollution patterns and demonstrate the effectiveness of machine learning in predictive analytics for environmental health.

## Installation Steps

1.  **Clone the Repository**
    ```bash
    git clone https://github.com/HusainAhmadKhan/Karachi_Air_Pollution_Prediction.git
    cd Karachi_Air_Pollution_Prediction
    ```

2.  **Set up a Virtual Environment (Recommended)**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install Required Libraries**
    ```bash
    pip install -r requirements.txt
    ```
    > **Note:** A `requirements.txt` file is not present in the repository. Please manually install the libraries listed below.

## Required Libraries
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- ipywidgets (for the interactive interface)
- Jupyter Notebook or Google Colab (for running the notebook)

## Instructions on How to Run the Project

1.  **Open the Notebook**
    - You can run the project locally using Jupyter Notebook or JupyterLab.
    - Alternatively, you can open the notebook directly in Google Colab using the provided link.

2.  **Load the Dataset**
    - The dataset file `Karachi Aga khan University Air Quality.xlsx` is included in the repository. Ensure it is in the same directory as the notebook.

3.  **Run the Notebook Cells Sequentially**
    - Execute the cells in order to perform:
        1.  Data loading and preprocessing.
        2.  Exploratory Data Analysis (EDA).
        3.  Feature engineering.
        4.  Model training (Linear Regression, Decision Tree, Random Forest).
        5.  Model evaluation.
        6.  Launch the interactive UI for prediction (if using the widget).

4.  **Using the Interactive Interface**
    - The final cells of the notebook include a simple interactive interface built with `ipywidgets`.
    - You can input environmental parameters such as PM1, temperature, humidity, hour, and day to get a real-time PM2.5 prediction.

## Expected Output

- **Exploratory Data Analysis:** You will see visualizations, including a correlation matrix heatmap and time-series plots, showing relationships between PM2.5 and other environmental factors.
- **Model Performance:** The notebook will output performance metrics (R² Score and Mean Squared Error) for each of the three trained models (Linear Regression, Decision Tree, and Random Forest).
- **Best Model:** Based on the report, the **Random Forest Regressor** is expected to achieve the highest prediction accuracy.
- **Interactive Prediction:** After running the widget cells, you will be able to use sliders and dropdowns to input values and receive an immediate PM2.5 prediction.

## Repository Structure
```
Karachi_Air_Pollution_Prediction/
├── Karachi Aga khan University Air Quality.xlsx  # Dataset
└── Karachi_Air_Pollution_Prediction.ipynb      # Main Jupyter Notebook
```

## Key Insights from the Project
- **PM1** has a very strong positive correlation with PM2.5 (~0.99) and is the strongest predictor.
- **Temperature** shows a slight negative relationship with pollution.
- **Humidity** has a moderate positive relationship with pollution.
- **Random Forest** outperformed Linear Regression and Decision Tree models due to its ability to capture complex, non-linear relationships.

## Future Improvements
- Incorporate additional weather data (wind speed, rainfall).
- Use deep learning models like LSTM for time-series forecasting.
- Collect and integrate data from multiple locations across Karachi.
- Perform hyperparameter tuning for better accuracy.
- Deploy the model as a real-time web application.

## Tools & Technologies
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, ipywidgets
- **Environment:** Google Colab, Jupyter Notebook

## GitHub Repository
[https://github.com/HusainAhmadKhan/Karachi_Air_Pollution_Prediction](https://github.com/HusainAhmadKhan/Karachi_Air_Pollution_Prediction)

## Google Colab Notebook
[https://colab.research.google.com/drive/1pOaH5ySZGrLICUe4aH5UD74VSPLCIS74?usp=sharing](https://colab.research.google.com/drive/1pOaH5ySZGrLICUe4aH5UD74VSPLCIS74?usp=sharing)
