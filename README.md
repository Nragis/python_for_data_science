# Python for Data Analysis 
## Data wrangling with Pandas, Numpy, and iPython
by Wes McKinney

# Project Description
This repository is my personal notes and scratch work in Jupyter Notebooks from
working through this book.

## Python Requirements
All python requirements are in [requirements.txt](requirements.txt) and can be 
installed using `pip install -r requirements.txt`. I recommend using a venv so
that this does not overwrite your personal python packages.

Any custom modules will be located in [PfDA](PfDA), and must be installed using
`pip install -e PfDA` (hopefully using a venv). This will install an editable 
package into your python environment, meaning that any changes to PfDA will be
immediately added to your environment.

To add your venv to, first activate your venv, then run `python -m ipykernel
install --user --name=<venv_name>`. Verify your installation by checking the 
kernel.json at the printed installation location.

## Jupyter Notebooks
All notebooks will be stored in [notebooks](notebooks) and organized in 
subfolders by chapter. These will contain the majority of the scratch work and
notes from my reading.