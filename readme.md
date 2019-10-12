# Setup and Installation
RDKit has been installed with a conda, because the package is not available via PyPI:
```
conda create -c rdkit -n my-rdkit-env rdkit
```
To install deepchem type in the command below. Please check that you have at least Python 3.5 when you run the command. Otherwise, it will fail
```
conda install -c deepchem -c rdkit -c conda-forge -c omnia deepchem-gpu=2.2.0
```