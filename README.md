# Hourly Energy Consumption Forecasting

## Overview
This project focuses on forecasting hourly energy consumption using advanced machine learning techniques. The main tool used for time-series forecasting is the **Prophet** library, along with standard Python data manipulation and visualization libraries. The notebook evaluates model performance using metrics such as Mean Absolute Percentage Error (MAPE), Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).

## Dataset
The dataset is provided by PJM. Here i have used PJM East region energ consumption data.
PJM Interconnection is a little-known company that operates the electric grid for a region stretching from New Jersey to North Carolina, and from Illinois to our nation's capital.

## Features
- Preprocessing and visualization of energy consumption data.
- Time-series modeling using **Prophet**.
- Evaluation of model performance using various metrics.
- Easy-to-use, modular code for quick experimentation.

## Requirements
The following Python libraries are required to run the notebook:

- `prophet`
- `numpy`
- `pandas`
- `seaborn`
- `matplotlib`
- `scikit-learn`

Install these dependencies by running:

```bash
pip install -r requirements.txt
```

## Usage
1. Clone the repository and navigate to the project directory:
   ```bash
   git clone <repository_url>
   cd <project_directory>
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook to explore the analysis and forecasting steps:
   ```bash
   jupyter notebook Hourly_Energy_Consumption.ipynb
   ```

## Key Functions and Metrics
### Functions:
- **mean_absolute_percentage_error(y_true, y_pred):** Calculates MAPE for evaluation.

### Metrics:
- **Mean Absolute Percentage Error (MAPE)**
- **Mean Absolute Error (MAE)**
- **Root Mean Squared Error (RMSE)**

## Visualization
The notebook uses `matplotlib` and `seaborn` for visualizing:
- Trends in energy consumption.
- Model forecasts vs. actual values.

## Notes
- Ensure the data file is available and properly preprocessed before running the notebook.
- Adjust the `Prophet` parameters to optimize forecasting for your specific dataset.

## Contributing
Contributions are welcome! Feel free to fork this repository and submit pull requests for improvements or additional features.

