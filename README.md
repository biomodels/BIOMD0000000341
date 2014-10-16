# BIOMD0000000341: Topp2000_BetaCellMass_Diabetes

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000341.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000341.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000341 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This model is from the article:  
** A model of beta-cell mass, insulin, and glucose kinetics: pathways to diabetes. **   
Topp B, Promislow K, deVries G, Miura RM, Finegood DT. _J Theor Biol._2000 Oct
21;206(4):605-19. [ 11013117](http://www.ncbi.nlm.nih.gov/pubmed/11013117),  
**Abstract:**   
Diabetes is a disease of the glucose regulatory system that is associated with
increased morbidity and early mortality. The primary variables of this system
are beta-cell mass, plasma insulin concentrations, and plasma glucose
concentrations. Existing mathematical models of glucose regulation incorporate
only glucose and/or insulin dynamics. Here we develop a novel model of beta
-cell mass, insulin, and glucose dynamics, which consists of a system of three
nonlinear ordinary differential equations, where glucose and insulin dynamics
are fast relative to beta-cell mass dynamics. For normal parameter values, the
model has two stable fixed points (representing physiological and pathological
steady states), separated on a slow manifold by a saddle point. Mild
hyperglycemia leads to the growth of the beta -cell mass (negative feedback)
while extreme hyperglycemia leads to the reduction of the beta-cell mass
(positive feedback). The model predicts that there are three pathways in
prolonged hyperglycemia: (1) the physiological fixed point can be shifted to a
hyperglycemic level (regulated hyperglycemia), (2) the physiological and
saddle points can be eliminated (bifurcation), and (3) progressive defects in
glucose and/or insulin dynamics can drive glucose levels up at a rate faster
than the adaptation of the beta -cell mass which can drive glucose levels down
(dynamical hyperglycemia).


