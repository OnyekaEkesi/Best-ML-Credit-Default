   ## Project Name: Best ML Algorithms to Predict Credit Default

## Introduction

**This project aims to explore and compare various machine learning (ML) algorithms for predicting credit default among corporate entities using financial data. The goal is to produce a comprehensive analysis document and accompanying code for each algorithm's performance, interpretability, and features. This analysis will aid in determining the most suitable algorithms for our existing models and potentially lead to model optimizations.By leveraging data-driven insights, this project aims to enhance our ability to predict and mitigate corporate credit defaults effectively.

### Table of Contents

1. [Project Name](#project-name)
2. [Project Overview](#project-overview)
3. [Getting Started](#getting-started)
   - [Prerequisites](#prerequisites)
   - [Installation](#installation)
   - [Usage](#usage)
   - [Test](#test)
   - [Streamlit App](#streamlit-app)
   - [Model Interpretability](#model-interpretability)
   - [Contributing](#contributing)
   - [License](#license)
   - [Project Organization](#project-organization)
   - [Project Life cycle](#Project-Life-cycle)
   - [Relevant External Links](#Relevant-External-Links)
   - [Names of Developers](#names-of-developers)


## Project Overview

**This Credit Default Prediction Project aims to enhance our understanding of machine learning algorithms' performance in predicting credit defaults among corporate entities. It involves exploring and comparing various algorithms, analyzing their performance metrics, interpretability, and feature engineering techniques.

## Getting Started

**These instructions will guide you through setting up and running the project on your local machine for development and testing purposes. Please follow these steps to get started.

## Prerequisites
    
    Before you begin, ensure you have met the following requirements:
    
**Python: 
The project is written in Python, so you need to have Python installed on your machine. You can download Python from python.org or use a package manager like Anaconda or Miniconda and follow up on the INSTALLATION steps.

 ## Installation

**Clone the project repository to your local machine ➡ Navigate to the project directory ➡ Create a virtual environment (optional but recommended) to isolate project dependencies ➡ Activate the virtual environment(On WindowsOn, macOS and Linux) ➡ Install the project dependencies.


**Setup - you only need to do this once

    ```bash
    # make sure your pip in your base Python installation is up-to-date
    python3 -m pip install -U pip
    # install the virtualenv package
    python3 -m pip install virtualenv

## Usage

    Now that you have installed the project, you can use it as follows:
    
**Run the Jupyter Notebook ➡ Open the project's Jupyter Notebook file in the notebook interface (e.g., project.ipynb) ➡ Follow the comment in the notebook to explore and analyze the project. 

**Create the virtual environment - also typically only run when needed

    ```bash
    # create a virtual environment in this directory called '.venv'
    python3 -m venv .venv
    # you should now see the folder `.venv` in your repo
    
**This is how you activate the virtual environment in a terminal and install the project dependencies

    ```bash
    # activate the virtual environment
    source .venv/bin/activate
    # install the requirements for this project
    pip install -r requirements.txt
    
## Tests

**It's highly recommended to get in the habit of writing tests, especially once you've identified something
concrete that you can refactor into a reusable bit of code. This project has been seeded with a minimal
working example of a [refactored function](src/data/make_dataset.py),
[a notebook that can import this code](notebooks/0.0-example.ipynb) and
[a unit test to test the code behaves as expected](tests/test_make_dataset.py).

**You can execute tests from the terminal by running `pytest`. IDEs like VSCode have built-in support for
executing and debugging tests through the "Testing" menu.

## Streamlit App

    If you want to use the Streamlit app for a user-friendly interface, follow these steps:
    
**Install Streamlit if you haven't already ➡ Run the Streamlit app

## Model Interpretability

**Interpreting the results of these machine learning models is essential for understanding their predictions and making informed decisions. In this section, we provide guidance on how to interpret the models used in this project as follows:

## Using Interpretability Tools

**We recommend using interpretability tools such as SHAP (SHapley Additive exPlanations) values, feature importance plots, or other model-specific methods to gain insights into the model's decision-making process. These tools can help answer questions like:

    Which features have the most significant impact on predictions?
    How does changing a feature value affect the model's output?
    What factors contribute to a specific prediction?
    
## Contributing

***We welcome contributions from the community to enhance and improve this project. If you're interested in contributing, please follow this step:

 Reach out to the group of developers for comprehensive guideline via this email: Exploreinterns2023@gmail.com


## License

This project is licensed under the EXPLORE AI, SOUTH AFRICA, which can be found in the internship-project-2301-03 FILE. Please review the terms of the license before using or contributing to the project.


## Project Organisation

```ascii
├── LICENSE            <- Contains information about the legal terms and conditions under which
|                         the code can be used.
|
├── README.md          <- The top-level README for developers using this project.
│
├── docs               <- Use markdown. If/when the project becomes more complex consider migrating
|                         to something like pdoc or sphinx depending on the nature of the project.
|                         Think carefully about what documentation should sit alongside the code
|                         and what you can rather include in docstrings.
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering), and a
│                         short `-` delimited description, e.g. `1.0-initial-data-exploration`.
|                         Refactor the good parts. Don't write code to do the same task in multiple
|                         notebooks. If it's a data preprocessing task, put it in a file like
|                         `src/data/make_dataset.py`. If it's useful utility code, refactor it to
|                         `src` and import accordingly. Only commit clean notebooks (clear all cell outputs).
│
├── requirements.txt   <- The requirements file for reproducing the environment.
|
├── src                <- Source code. Refactor clean, re-usable code here.
│   │
│   ├── data           <- Separate your code base into logical groups, e.g. data, features, models, visualisation, etc.
│   │   └── make_dataset.py
│   └── ...
|
├── tests              <- Unit tests. Filename should start with "test_".
    └── test_make_dataset.py
```

## Project Life Cycle: 

Data Preprocessing ➡ Exploratory Data Analysis (EDA) ➡ Model Development ➡ Model Training and Evaluation ➡ Hyperparameter Tuning ➡ Deployment ➡ Testing ➡ Documentation ➡ Presentation and Reporting

## Relevant external links

1. Notion: https://www.notion.so/explore-ai/Best-ML-algorithms-to-predict-credit-default-230f3a4d2892470eb30a4966345eca12
2. S3 bucket:

## Names of Developers

- Onyeka Ekesi: Project Lead
- Midrar Abubakar: Vice Project Lead
- Steve Mutiso: Technical lead
- Moses Bokaba: Asst Technical lead
- Akanni Oladimeji Peterson: Administrative Lead
- Chege Kennedy: Asst Administrative Lead

## Note: 
* Due to the nature of this project, code cannot be shared publicly.
