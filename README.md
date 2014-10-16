# BIOMD0000000082: Model_1

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000082.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000082.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000082 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This model was created according to the paper _Inhibition of Adenylate Cyclase
Is Mediated by the High Affinity Conformation of the alpha2-Adrenergic
Receptor_ published in 1988.

The figure4 (steady state curve) in the paper has been simulated having the
same plot with Copasi 4.0.19 (development) and roadRunner(online).Because the
initial concentration of R and D were not given in the paper ,so we gave it
1e-9 Mol/L and 1e-8 Mol/L respectively.

Pay attention that the simulations of steady state concentration of species in
arbitrary units are shown for figure4 and figure6 in the paper.


