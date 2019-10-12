# Setup and Installation
RDKit has been installed with a conda, because the package is not available via PyPI:
```
conda create -c rdkit -n my-rdkit-env rdkit
```
Or try the command below if you want to use both rd-kit and deepchem:
```
conda install -c deepchem -c rdkit -c conda-forge -c omnia deepchem=2.0.0 python=3.5
```
The virtual conda environment was used to isolate this amazing, well-built package which has a potential of destroying all of my global package dependencies :)) 