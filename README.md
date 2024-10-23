# PricePoint Pro
 
 ## Overview
This project consists of various Python modules implementing design patterns, machine learning pipelines, and data preprocessing techniques. It demonstrates the use of design patterns like Factory, Strategy, and Template in Python, along with a comprehensive implementation of a machine learning model development and deployment pipeline using ZenML.

## Structure
The project is organized into the following directories and key files:

### Design Patterns
1. **Factory Design Pattern**: `extraction/factory_design_patter.py`
   - Implements a coffee machine interface to create various types of coffee using the Factory design pattern.

2. **Strategy Design Pattern**: `extraction/strategy_design_pattern.py`
   - Implements different payment methods in a shopping cart using the Strategy design pattern.

3. **Template Design Pattern**: `extraction/template_design_pattern.py`
   - Implements a dining template to outline the steps involved in serving different types of dinner using the Template design pattern.

### Machine Learning Pipelines
1. **Training Pipeline**: `pipelines/training_pipeline.py`
   - Defines an end-to-end machine learning pipeline including data ingestion, preprocessing, model training, and evaluation using ZenML.

2. **Deployment Pipeline**: `pipelines/deployment_pipeline.py`
   - Manages the deployment of trained models and serves predictions.

### Data Processing and Modeling
- Located under `src/`, modules in this directory implement various data processing strategies like handling missing values, feature engineering, data splitting, model building, and evaluation:
   - `data_splitter.py`, `feature_engineering.py`, `handle_missing_values.py`, `model_building.py`, `model_evaluator.py`, `outlier_detection.py`.

### Utility Scripts
- **Deployment Runner**: `run_deployment.py`
  - A script to run the deployment pipeline and manage the lifecycle of prediction services.

- **Pipeline Runner**: `run_pipeline.py`
  - A script to execute the training pipeline and inspect experiments via MLflow UI.

## Dependencies
Ensure all dependencies are installed using the following pip command:

```bash
pip install -r requirements.txt
```

The `requirements.txt` file should include all libraries and their versions required to run the code, such as `scikit-learn`, `pandas`, `numpy`, `zenml`, `mlflow`, etc.

## Running the Code
1. To run the training pipeline:
   ```bash
   python run_pipeline.py
   ```

2. To deploy and manage the lifecycle of machine learning models:
   ```bash
   python run_deployment.py
   ```

## Contributing
Contributions to this project are welcome. Please ensure that you update tests as appropriate and adhere to the existing coding style.

Further details and documentation can be added here, such as code usage examples, additional configuration details, or contact information for contributors seeking support.

