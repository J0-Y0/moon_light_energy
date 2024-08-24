# Moon Light Energy Data Analysis

This repository contains the exploratory data analysis (EDA) and dashboard development for the Moon Light Energy project. The main EDA work is performed in the Jupyter notebook, and a Streamlit application is developed for interactive data visualization.

## Project Structure

```bash
moon_light_energy/
├── .streamlit/
│   └── config.toml                # Configuration for Streamlit
├── .vscode/
│   └── settings.json              # VSCode settings for the project
├── .github/
│   └── workflows/
│       ├── unittests.yml          # GitHub Actions workflow for running unit tests
├── .gitignore                     # Git ignore file
├── requirements.txt               # Python dependencies
├── README.md                      # Project documentation
├── notebooks/
│   ├── __init__.py
│   ├── EDA_analysis.ipynb         # Main notebook for EDA
│   └── README.md                  # Additional information about the notebooks
├── tests/
│   ├── __init__.py                # Unit tests initialization
├── app/
│   ├── __init__.py
│   ├── main.py                    # Main Streamlit application script
│   ├── utils.py                   # Utility functions for data processing and visualization
└── scripts/
    ├── __init__.py
    └── README.md                  # Details about the scripts
