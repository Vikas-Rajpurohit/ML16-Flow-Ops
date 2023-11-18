# ML16-Flow-Ops
End to End MLOps Project

![Alt text](image.png)

# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/Vikas-Rajpurohit/ML16-Flow-Ops
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n mlproj python=3.8 -y
```

```bash
conda activate mlproj
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up you local host and port
```



## MLflow

[Documentation](https://mlflow.org/docs/latest/index.html)


##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/Vikas-Rajpurohit/ML16-Flow-Ops.mlflow \
MLFLOW_TRACKING_USERNAME=Vikas-Rajpurohit \
MLFLOW_TRACKING_PASSWORD=2c5711c996a9fabd49d990030d6c35ec94678387 \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/Vikas-Rajpurohit/ML16-Flow-Ops.mlflow

export MLFLOW_TRACKING_USERNAME=Vikas-Rajpurohit

export MLFLOW_TRACKING_PASSWORD=2c5711c996a9fabd49d990030d6c35ec94678387

```