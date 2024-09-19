# Optimizing Purchase Predictions: A Machine Learning Classification Model

## Overview
This project focuses on developing a machine learning model to predict purchase behaviors. By leveraging advanced classification techniques, the goal is to enhance prediction accuracy and provide valuable insights for optimizing marketing strategies.

## Features
- **Data Preprocessing**: Comprehensive cleaning of data to address duplicates and missing values.
- **ML Pipeline**: End-to-end pipeline implemented using Jupyter notebooks and Python scripts.
- **Prediction Model**: Classification model developed to predict purchase behaviors with high accuracy.
- **Airflow DAG**: Automated data pipeline using Apache Airflow to streamline data processing and model execution.

## Files
- `P2M3_fahmi_GX.ipynb`: Jupyter notebook for model development, including data exploration and training.
- `P2M3_fahmi_DAG.py`: Python script defining the Airflow DAG for automating the data pipeline.
- `P2M3_fahmi_data_raw.csv`: Original dataset before preprocessing.
- `P2M3_fahmi_data_clean.csv`: Processed dataset ready for model training and evaluation.

## Usage
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/fazfahmi/Project-2.git
   cd Project-2
2. **Install the necessary Python libraries by running**:
    ```bash
   pip install -r requirements.txt
3. **Start Jupyter notebooks to explore the data and train the model**:
    ```bash
    jupyter notebook P2M3_fahmi_GX.ipynb
4. **Ensure Apache Airflow is properly installed and configured, then use the provided DAG to automate the data pipeline**:
    ```bash
    airflow dags trigger -d P2M3_fahmi_DAG.py

## License
This project is licensed under the MIT License.
   
