# The Python Workshop Mini Project

## Navigating the repository 
The repository contains:
1. "mini_project_workflow.ipynb" --- this notebook contains the entire project: questions that were addressed, solutions, supporting plots and all analytics;
2. "python_workshop_miniproject.code-workspace" --- a configuration of the workspace;
2. "miniproject.toml" --- a configuration file of the project.

## Basic requirements
Python >= 3.12

## Installation and the first run:
```bash 
# install virtualenv to set up your Python environments:
pip install virtualenv
# create a virtual environment:
python -m venv venv
# activate the virtual environment (Linux/Mac OS):
source venv/bin/activate 
# upgrade pip to its latest version:
pip install --upgrade pip
# install the dependencies of the project:
pip install -e .[dev]     
``` 

### Notes
All code cells of the notebook were executed and all markdown cells were rendered in advance.
