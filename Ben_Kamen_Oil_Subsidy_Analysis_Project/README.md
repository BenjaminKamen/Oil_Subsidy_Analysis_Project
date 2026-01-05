# Oil_Subsidy_Analysis

<a target="_blank" href="https://cookiecutter-data-science.drivendata.org/">
    <img src="https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter" />
</a>

Ben Kamen's personal data science project: analyzing potential predictors of oil subsidies across countries.

To read the analysis process, go through the notebooks in notebooks_as_html.

## Project Organization. Made with the help of cookie cutter data science repo

```
├── Makefile           <- Makefile with convenience commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original data dump from combining extrnal data.
│
├── docs               <- A default mkdocs project; see www.mkdocs.org for details
│
├── models             <- Trained and serialized models.
|
├── final_predictions  <- Predictions on the test data from the models
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
|
├── notebooks_as_html <-- Final notebooks converted to html files for ease of reading
│
├── pyproject.toml     <- Project configuration file with package metadata for 
│                         oil_subsidy_analysis and configuration for tools like black
│
├── references         <- Citations for data sources
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.cfg          <- Configuration file for flake8
│
└── oil_subsidy_analysis   <- Source code for use in this project.
    │
    ├── __init__.py             <- Makes oil_subsidy_analysis a Python module
    │
    ├── config.py               <- Store useful variables and configuration
    │
    ├── dataset.py              <- Scripts to download or generate data
    │
    ├── features.py             <- Code to create features for modeling
    │
    ├── modeling                
    │   ├── __init__.py 
    │   ├── predict.py          <- Code to run model inference with trained models          
    │   └── train.py            <- Code to train models
    │
    └── plots.py                <- Code to create visualizations
```

--------

