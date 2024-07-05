# Disease-Classification

## Workflows

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline
8. Update the main.py
9. Update the dvc.yaml
10. app.py

# How to run?

### STEPS:

Clone the repository

```bash
https://github.com/Niroshan2001/Disease-Classification
```

### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n cnncls python=3.8 -y
```

```bash
conda activate cnncls
```

### STEP 02- install the requirements

```bash
pip install -r requirements.txt
```

```bash
# Finally run the following command
python app.py
```

## MLflow

- [Documentation](https://mlflow.org/docs/latest/index.html)

- [MLflow tutorial](https://youtu.be/qdcHHrsXA48?si=bD5vDS60akNphkem)

##### cmd

- mlflow ui

### dagshub

[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/Niroshan2001/Disease-Classification.mlflow \
MLFLOW_TRACKING_USERNAME=Niroshan2001 \
MLFLOW_TRACKING_PASSWORD=f35f5129ba1d7804ee0afbbf327ed31a7db412a8 \
python script.py

Run this to export as env variables:

```bash

$env:MLFLOW_TRACKING_URI = "https://dagshub.com/Niroshan2001/Disease-Classification.mlflow"


$env:MLFLOW_TRACKING_USERNAME = "Niroshan2001"

$env:MLFLOW_TRACKING_PASSWORD = "f35f5129ba1d7804ee0afbbf327ed31a7db412a8"

```
