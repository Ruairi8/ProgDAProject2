# Programming for Data Analytics Project 2
---
## Description
 I will investigate the Wisonson Breast Cancer (original) dataset. The project requirements are as follows:
- Undertake an analysis/review of the dataset and present an overview and background.
- Provide a literature review on classifiers which have been applied to the dataset and
  compare their performance
- Present a statistical analysis of the dataset
- Using a range of machine learning algorithms, train a set of classifiers on the dataset (using
  SKLearn etc.) and present classification performance results. Detail your rationale for the
  parameter selections you made while training the classifiers.
- Compare, contrast and critique your results with reference to the literature
- Discuss and investigate how the dataset could be extended – using data synthesis of new
  tumour datapoints
- Document your work in a Jupyter notebook.
- As a suggestion, you could use Pandas, Seaborn, SKLearn, etc. to perform your analysis.
- Please use GitHub to demonstrate research, progress and consistency.


## Repository Contents
- Jupyter notebook: main.ipynb
- csv file: tumor.csv
- README.dm
- .gitignore 

## Programming languages and packages used
- Python version: 3.7
- Matplotlib
- Seaborn
- Pandas
- Numpy
- Sklearn
- time
- random
- urllib

## How to Run Jupyter
Jupyter Notebook is an interactive environment for writing and running code. The Notebook in my repository is linked with the iPython kernel and therefore runs Python code. Code cells allow users to run code by clicking 'shift-enter'or by clicking the ▶ button in the toolbar. 'ctrl-enter' runs a selected cell and enters command mode. The Kernel is used to manage running of the code, it can be restarted to nullify all cell outputs or interrupted.

Installation documentation for Jupyter can be found, on [ReadTheDocs](https://docs.jupyter.org/en/latest/install.html). More advanced usage of Jupyter notebook can be found [here](https://jupyter-notebook.readthedocs.io/en/latest/).

For a local installation, it can be installed via pip by running:
``` python
pip install notebook
```
Jupyter is launched with in a local installation:
``` python
jupyter notebook
```
Or for running a Jupyter notebook remotely you need some configuration. See [Running a notebook server](https://jupyter-notebook.readthedocs.io/en/stable/public_server.html).