# deep classifier project

## workflow

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline
8. Test run pipeline stage
9. run tox for testing your package
10. Update the dvc.yaml
11. Run "dvc repro" for running all the stages in pipeline


![img](https://raw.githubusercontent.com/c17hawke/FSDS_NOV_deepCNNClassifier/main/docs/images/Data%20Ingestion%402x%20(1).png)


STEP 1: Set the env variable | Get it from dagshub -> remote tab -> mlflow tab


MLFLOW_TRACKING_URI = https://dagshub.com/Mritunjay1121/DEEPCNN_CLASSIFIER.mlflow 
MLFLOW_TRACKING_USERNAME=Mritunjay1121 
MLFLOW_TRACKING_PASSWORD=01a8c0c421c701dc3b9ece7eccb51ca5e0f38ef2 



STEP 2: install mlflow

STEP 3: Set remote URI

STEP 4: Use context manager of mlflow to start run and then log metrics, params and model