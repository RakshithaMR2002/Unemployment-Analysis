# Unemployment Analysis During COVID-19 in India using Machine Learning

This project focuses on analyzing the specific impact of the COVID-19 pandemic on unemployment rates within India. It utilizes machine learning techniques to identify key contributing factors and predict trends within the Indian context. We leverage publicly available datasets, focusing on India's unique socio-economic landscape during the pandemic.

## Project Goals

* **India-Specific Data Analysis:** Investigate how COVID-19-related factors, including lockdowns, regional variations, and government policies, influenced unemployment in India.
* **Time-Series Analysis:** Model the temporal evolution of Indian unemployment during the pandemic, capturing the distinct peaks and troughs of economic disruption.
* **Regional and Sectoral Impact Assessment:** Examine the varying impact of the pandemic on unemployment across different Indian states and economic sectors (e.g., agriculture, manufacturing, services).
* **Predictive Modeling:** Develop machine learning models to forecast unemployment trends in India during and post-pandemic.
* **Visualization and Reporting:** Present findings through clear and informative visualizations and reports, highlighting the pandemic's impact on the Indian labor market.

## Datasets

* **Centre for Monitoring Indian Economy (CMIE) data:** Crucial for detailed unemployment statistics in India.
* **Ministry of Statistics and Programme Implementation (MOSPI) data:** Provides economic indicators relevant to India.
* **National Sample Survey Office (NSSO) data:** Offers insights into employment patterns.
* **Indian Council of Medical Research (ICMR) data:** COVID-19 infection and testing data.
* **Reserve Bank of India (RBI) data:** Economic indicators and policy responses.
* **State-level government data:** Detailed regional information.

## Technologies Used

* **Python:** For data manipulation, analysis, and machine learning.
* **Libraries:**
    * `pandas`: Data manipulation and analysis.
    * `numpy`: Numerical computing.
    * `scikit-learn`: Machine learning algorithms.
    * `matplotlib` and `seaborn`: Data visualization.
    * `statsmodels`: Time-series analysis and statistical modeling.
    * `Prophet` or `ARIMA` for time series forecasting.
* **Jupyter Notebooks:** For interactive data exploration and model development.
## Getting Started

1.  **Clone the repository:**

    ```bash
    git clone [repository URL]
    cd COVID_Unemployment_India
    ```

2.  **Create a virtual environment (recommended):**

    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On macOS and Linux
    venv\Scripts\activate  # On Windows
    ```

3.  **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4.  **Download the datasets:** Place the relevant India-specific COVID-19 and unemployment datasets in the `data/` directory.

5.  **Run the Jupyter notebooks:**

    ```bash
    jupyter notebook notebooks/india_covid_analysis.ipynb
    ```

    Follow the instructions within the notebooks to explore the data, perform time-series analysis, build prediction models, and generate visualizations.

## Model Evaluation

Model performance will be evaluated using metrics appropriate for time-series forecasting and regression, including:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* Mean Absolute Percentage Error (MAPE)
* R-squared (R2)
* Time-series specific metrics, like AIC and BIC.
