
# Wine Quality Prediction: End-to-End Machine Learning Pipeline

This repository contains an end-to-end machine learning project for predicting wine quality using a structured pipeline. The project integrates tools such as **DagsHub** for version control and collaboration and **MLflow** for tracking experiments.

## Project Structure

```
END2END-WINEQUALITY/
│
├── artifacts/                   # Intermediate data and model artifacts
│   ├── data_ingestion/          # Raw data and ingestion pipeline
│   ├── data_transformation/     # Data preprocessing and feature engineering
│   ├── data_validation/         # Data validation and schema checks
│   ├── model_evaluation/        # Evaluation metrics and reports
│   └── model_trainer/           # Training artifacts and saved models
│
├── config/                      # Configuration files
├── logs/                        # Logging outputs
├── research/                    # Notebooks and exploratory analysis
├── src/                         # Source code
├── templates/                   # Template files (e.g., HTML templates)
├── venv/                        # Virtual environment files
├── .gitignore                   # Git ignore file
├── app.py                       # Flask API for model serving
├── Dockerfile                   # Docker container configuration
├── LICENSE                      # License for the repository
├── main.py                      # Entry point for running the pipeline
├── params.yaml                  # Hyperparameters and global settings
├── README.md                    # Project documentation
├── requirements.txt             # Python dependencies
├── schema.yaml                  # Data schema for validation
├── setup.py                     # Package setup file
└── template.py                  # Codebase template
```

## Features

- **Data Ingestion**: Automates loading raw data into the pipeline.
- **Data Validation**: Ensures input data quality with schema validation.
- **Data Transformation**: Handles preprocessing, encoding, and feature engineering.
- **Model Training**: Trains models using sklearn and tracks experiments with MLflow.
- **Model Evaluation**: Provides evaluation metrics like RMSE, MAE, and R².
- **Deployment**: Exposes the trained model as an API using Flask.

## Tools and Technologies

- **Python**
- **DagsHub**: Collaboration and version control.
- **MLflow**: Experiment tracking.
- **Flask**: Model serving API.
- **Docker**: Containerization.
- **YAML**: Configuration management.
- **Git**: Version control.