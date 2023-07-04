# Title
Atoms selection using MOLINFO keyword in PLUMED

# Aim
The aim of this tutorial is to introduce users to illustrate how to select atoms using MOLINFO function in PLUMED.

# Objective
Once this tutorial is completed users will be able to
- Use advanced selection tools provided by MDanalysis, MDtraj and VMD using MOLINFO keyword

# Setting up the software
## Installation with conda:
Make sure that you have conda in your machine and typing conda in the terminal.

``` conda ```

Please install the latest version of conda using this [link](https://docs.conda.io/en/latest/miniconda.html). After installation create a conda environment using the below command:

``` conda create --name tutorial-molinfo ```

``` conda activate tutorial-molinfo```

Finally you need to install the softwares required for this tutorial by using the below conda command.

``` conda install -c conda-forge plumed mdtraj mdanalysis vmd-python ```

**IMPORTANT: DO NOT FORGET TO ACTIVATE THE CONDA ENVIRONMENT "tutorial-molinfo" EVERYTIME YOU OPEN A NEW TERMINAL**

