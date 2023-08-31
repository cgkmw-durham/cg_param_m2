# cg_param_m2
-----------------Outdated version of code: See default branch for most recent release---------------

Coarse-grained mapping and parametrisation for the Martini 2 forcefield

Run with: ./cg_param.py "[SMILES]" [name].gro [name].itp

Outputs .gro and .itp files compatible with Gromacs

Dependencies:

*numpy/scipy
*RDKit
*requests

The easiest way to install these dependencies is with conda

~~~~
$ conda create -c rdkit -n cg_param rdkit numpy scipy requests
$ conda activate cg_param
~~~~

A full description of the mapping and parametrisation procedures, can be found in the following paper:
T.D. Potter, E.L. Barrett and M.A. Miller, Automated Coarse-Grained Mapping Algorithm for the Martini Force Field and Benchmarks for Membrane–Water Partitioning, J. Chem. Theory Comput., 2021, https://doi.org/10.1021/acs.jctc.1c00322.
