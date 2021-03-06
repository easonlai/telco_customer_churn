# Telco Customer Churn

This is a sample code repository of the telco customer churn analysis or prediction by the classification/regression model for experiment and learning purposes. The sample dataset is also published in [Kaggle (Sample Telco Customer Churn Dataset)](https://www.kaggle.com/datasets/easonlai/sample-telco-customer-churn-dataset).

Contents:
* data/WA_Fn-UseC_-Telco-Customer-Churn_R2.csv <-- Sample dataset (7,011 records) of telco customer churn with corresponding churn label.
* data/WA_Fn-UseC_-Telco-Customer-Churn_R2_Test.csv <-- Dataset with 21 records for testing purposes.
* batch_scoring_with_aml_model_api.ipynb <-- Notebook to demonstrate how to consume trained classification model from [Azure Machine Learning](https://docs.microsoft.com/en-us/azure/machine-learning/overview-what-is-azure-machine-learning) [(AutoML)](https://docs.microsoft.com/en-us/azure/machine-learning/concept-automated-ml)'s [endpoint](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-consume-web-service?tabs=python) and perform batch scoring for testing dataset.
* Delta_Table_Merge_Demo.html <-- Sample of how to perform Azure Databricks Delta Table Merge. It demonstrates how to get daily CSV file updates into a master table in Delta Table format.
* Delta_Table_Merge_Demo.ipynb <-- Sample of how to perform Azure Databricks Delta Table Merge. It demonstrates how to get daily CSV file updates into a master table in Delta Table format.

Enjoy!



