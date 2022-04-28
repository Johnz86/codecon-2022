# CODECON Healthcare and Machine Learning

Sample notebooks shown on CODECON 2022 in Bratislava.

## Quickstart
```
py -m venv .
./scripts/activate
pip install notebook
```

## Ethical Report

This example has low requirements on performance and is good for starters.
```
pip install verifyml==0.0.5 pandas sklearn seaborn matplotlib
jupyter notebook ./notebooks/ethical-report-heart-disease-classification.ipynb
```

## MONAI

You should have fairly powerfull machine to run this.
```
pip install monai monailabel monai-deploy-app-sdk matplotlib
jupyter notebook  ./notebooks/MONAI-2d-classification.ipynb
```