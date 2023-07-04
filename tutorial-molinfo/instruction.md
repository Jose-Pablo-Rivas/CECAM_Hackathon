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

# Resources

Data needed to complete the exercise of this tutorial can be found on [Github]().

``` git clone ```

There are two files in the folder:
- 1AKI.xtc (trajectory for the analysis)
- 1AKI.pdb (reference conformation for MOLINFO functionality)

Also there a exercise-1 folder containing a plumed input file with the solution. Please go through this exercise and understand it for doing remaining exercises.

# exercise-1

- Calculate the radius of gyration for C-alpha atoms of first 10 residues of the protein.
- Calculate the distance between C-alpha atoms of residue 1 and 30 of the protein.

**Please read the MDAnalysis and MDTraj documentation if you are not familiar with their atom selection method.**

# exercise-2

- Calculate distance between geometric center of C-alpha atoms of first 5 residues and last 5 residues using MDAnalysis and MDtraj modules.

# exercise-3

- Calculate the hydrogen bond contacts as in alpha-helic structure of the protein for the protein  

