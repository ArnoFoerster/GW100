# GW100
GW100 data repository and post processing tools


structures
----------
directory containig the structures in xyz format


data
----
directory containing the contributed data sets

data stored in json files with the fields:
code 
code_version
orbital (HOMO, HOMO-1, LUMO)
calc_type (dft@functional, g0w0@functional, ...)
basis (PW, Gaussian, )
basis_name 
basis_size (cardinallity or energy cutoff)
data {cas: value}




scripts
-------
scripts for postprocessing
