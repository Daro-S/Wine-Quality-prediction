```bash
python -m venv vwineQualityPre
```

```bash
.\vwineQualityPre\Scripts\activate
```

```bash
pip install -r requirements.txt
```

## Workflows

1. Update config.yaml
2. Update schema.yaml
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline
8. Update the main.py
9. Update the app.py

## Mlflow UI

## Dagshub remote server

Run this to export as env variables:

export MLFLOW_TRACKING_URI=https://dagshub.com/darosim.itdev/Wine-Quality-prediction.mlflow

export MLFLOW_TRACKING_USERNAME=darosim.itdev

export MLFLOW_TRACKING_PASSWORD=c63426cbd6f6a12861a78c26d0cb97a9235a1150
