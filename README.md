

# Lie-Symmetries
Lie_Symmetry is a MATLAB code that provides a tool for searching symmetries in nonlinear models in order to convert a non-observable model observable (respectively, identifiable). Those models are described by ordinary differential equations and restrict to rational functions, despite of this restriction, there are a wide range of models included in. 

This semi-automatic algorithm can study models with initial conditions (parametric, numeric or a combination of both, they can be known or unknown), input functions (known or unknown) initial conditions. 

# Requirements
Lie_Symmetry requires a MATLAB installation with the Symbolic toolbox. It is only necessary to download the folder that includes two folders and one main programme:
 - FUNCTIONS. This folder includes all the necessary functions to run the programme.
 - MODELS. This folder includes some models. The user can create more models by following the examples already included and saving the corresponding file in the same folder.
 - Lie-Symmetry. This file is the main programme. The user can choose the degree of the infinitesimal polynomial, its type (univariate, partially variate or multivariate) and the maximum degree of Lie series (when the reparametrization need it). 
