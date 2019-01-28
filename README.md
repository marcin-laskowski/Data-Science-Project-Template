# Data Science Project Template

## Idea

It is very important to be consistent while working in the field of Machine Learning or Data Science. Due to that fact the special project template was created.

It is worth to have principles to keep organized:
1. Implementing version control
2. Setting up a virtual environment or docker containers
3. Separating raw data, intermediate data, and final data
4. Documenting work
5. Separate modules for custom functions


## Structure

```
├── README.md            <- Description of the project with comments
|                           about the files that are included.
|
├── LICENSE              <- license to the project
│
├── models               <- Trained and serialized models, model
│                           predictions or model summaries to deploy
│
├── notebooks            <- Jupyter notebooks. Naming convention:
│                           E.g. `1.2-data-exploration`.
│
├── reports              <- HTML, PDF, and LaTeX.
│   └── figures          <- Generated figures
│
├── requirements.txt     <- File for reproducing the environment
│                           `$ pip freeze > requirements.txt`
├── dataset
│   ├── external         <- Third party sources.
│   ├── interim          <- In-progress intermediate data.
│   ├── processed        <- The final data sets for modelling.
│   └── raw              <- The original, immutable data.
|
├── Dockerfile           <- docker file
|
├── docker-compose.yml   <- docker compose
|
├── docs                 <- additional documents
│
└── src                  <- Source code for use in this project.
    ├── __init__.py      <- Makes src a Python module.
    │
    ├── main.py          <- Main script.
    │
    ├── make_data.py     <- Scripts to download or generate data.
    |
    ├── models.py        <- Script with all define models
    │                
    ├── custom_func.py   <- Various custom functions to import.
    │
    └── visalize.py      <- Scripts to create visualizations.            
```
