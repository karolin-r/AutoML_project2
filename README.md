# A decision support system for explainability techniques

The goal of this project is to develop a decision support system that automates the selection of interpretable techniques based on dataset characteristics and quantitative evaluation metrics. The increasing complexity of machine learning models demands transparent and interpretable explanations for informed decision-making. Our system aims to enhance the accessibility of interpretability by recommending the most suitable technique for a given dataset, promoting robust and understandable machine learning models.

# Setup

``````bash
conda create -n automl2 python=3.9.18 -c conda-forge
conda activate automl2
pip install -r requirements.txt
``````

# Data and files

AutoML_project2_Karolin.ipynb - main code
datasets folder - contain all datasets that were used
metrics.py and metrics_rules.py - functions for evaluation metrics
anchor_utils.py - needed for using ANCHOR

