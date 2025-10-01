Fire Risk Model Validation using ROC Analysis

Overview
This script validates fire risk models using ROC (Receiver Operating Characteristic) analysis by comparing actual fire locations with predicted risk scores from a risk map.

What It Does
Loads fire occurrence data and risk map raster
Extracts risk scores at fire locations
Generates random background points for comparison
Calculates ROC curve and AUC score
Creates visualization of model performance

Run the Project
Install: pip install -r requirements.txt
Run: jupyter notebook forest_classification.ipynb
Follow the notebook steps

Output
The script generates:
ROC curve plot (roc_ffrm_corrected.png)
AUC score with interpretation
Summary statistics of risk scores