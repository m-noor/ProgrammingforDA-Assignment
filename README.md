# Programming for Data Analysis - Assignment
## Assignment for the GMIT HDip in Data Analysis Course

### Brief introduction
This repository is concerned with the use of Python `numpy.random` package. It contains the following files:

1. [README.md](README.md) (this file)
1. [ProgrammingforDA-Assignment.ipynb](ProgrammingforDA-Assignment.ipynb) - a Jupyter Notebook written in Python
1. [ProgrammingforDA-Assignment.pdf](ProgrammingforDA-Assignment.pdf) - PDF version of the Notebook. Note this is for reference only as the notebook is not accurately reproducible through conversion to PDF.
1. [Programmingfor-DA-assignment-instructions.pdf](Programmingfor-DA-assignment-instructions.pdf) - instructions for the assignment, for future reference only

### Pre-requisites for running the notebook
This notebook relies on the following libraries, so please ensure you have these installed on your machine before running.

1. `numpy`
1. `plotly`
1. `scipy`
1. `sympy`
1. `ipywidgets`

### Troubleshooting / known issues
Plotly seems not capable of handling multiple large plots within a single notebook, as each plot actually contains the data points within itself, rather than referencing variables. Due to this, interactivity in plots might not work until the particular cell is run manually, especially for those with ipywidget sliders.
