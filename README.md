# Moon Light Energy Data Analysis

This repository contains the exploratory data analysis (EDA) and dashboard development for the Moon Light Energy project. The main EDA work is performed in the Jupyter notebook, and a Streamlit application is developed for interactive data visualization.

## Main Project Structure

```bash
moon_light_energy/
├── .gitignore                     # Git ignore file
├── requirements.txt               # Python dependencies
├── README.md                      # Project documentation
├── notebooks/
│   ├── __init__.py
│   ├── EDA_analysis.ipynb         # Main notebook for EDA
│   └── README.md                  # Additional Insights on the EDA Performed
```
# Notebooks

The primary data analysis work is located in the `EDA_analysis.ipynb` notebook under the `notebooks/` directory. This notebook includes:

- **Data Quality Check:** Identifying missing values, outliers, and incorrect entries.
- **Data Cleaning:** Handling anomalies and filling missing values.
- **Wind Analysis:** Using Polar plots to analyze wind speed and direction.

Further details about the analysis can be found in the [README.md](/notebooks/README.md)  within the `notebooks/` folder.

# Streamlit Dashboard

An interactive dashboard has been developed using Streamlit, available in the dashboard-dev feature branch. To access the streamlined dashboard, switch to this branch.

# Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/J0-Y0/moon_light_energy.git
   cd moon_light_energy
2. **Create a virtual environment:**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

3. **Install the required dependencies:**

    ```bash
    pip install -r requirements.txt
4. **Get the EDA  under the `notebooks/` directory:**


## License
This project is licensed under the MIT License. See the [LICENSE](/LICENSE) file for details.

