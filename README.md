This is the case study of basic machine learning in chemistry application.

# No need to download the repository to run the tutorial!
No Python environment on your computer? No problem! You can directly run the tutorial in your browser without installing anything.
Please directly click this icon:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Liu-group/MLbook/HEAD?filepath=JupyterNotebook%2Fcase_study.ipynb)

A Jupyter notebook will automatically launch in your browser.

# Instructions to run the case study locally on your computer
If you prefer to download the repository to your own computer rather than running with Binder, please set up your environment based on the following instructructions:
1. Clone the repository to your local computer by running
``` git clone https://github.com/Liu-group/MLbook.git 
```

1. Make sure that Anaconda is installed on your computer.

1. Set up the conda environ needed for this case study by running
```conda env create -f environment.yml
```
Here, the environment.yml file is provided in the top-level folder of this repository

1. Now you should have a new conda environment called ```case_study```. All the Python packages needed for the case study has been automatically installed when you create the ```case_study``` environment using the ```environment.yml``` file provided.
1. Activate the conda environment
```conda activate case_study```
1. You can then lunch jupyter notebook and run the test cases! 

# If you want to run the study in an existing conda environment without using our environment.yml file
The best way to make sure all Python packages compatible with the case study is to set up the environment with the provided environment.yml file. If you insist not using it, then please check your own conda environment to make sure you have the compatible version of scikit-learn installed.
** The recommended version of scikit-learn to use with this case study is 0.20.3 to 0.22.1. Versions newer than 0.22.1 will not work. **
