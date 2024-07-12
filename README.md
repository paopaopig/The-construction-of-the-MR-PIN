# The-construction-of-the-MR-PIN

Description of the project file: This project was compiled using python3.9.

1. All datasets used in the paper are in the 'datasets' package.

2.The code for building MR-PIN is in the 'code' package,

where, (1) the 'MR-PIN.py' is the main code for building MR-PIN;
       (2) the 'gene_dis.py', 'sub_dis.py', 'complex_dis.py', 'orth_dis.py' can construct 1-4 layers of subnets of MR-PIN separately；
       (3) the 'construction_of_DPIN.py' and the 'construction_of_RDPIN.py' are used to build DPIN and RDPIN;
       (4) the 'FSPIN-ls-feature-selection.py' and the 'construction_of_FSPIN.py' are used to build FSPIN;
       (5) the 'network_based_centralities.py',  'PEC_method.py', 'WDC_method.py', 'JDC_method.py' are node ranking methods used to verify the performance of each network.
