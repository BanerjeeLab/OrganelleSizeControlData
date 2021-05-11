# Repository Information
This repository stores the data used in the paper [Size regulation of multiple organelles competing for a shared subunit pool](https://doi.org/10.1101/2020.01.11.902783).

# Description of the data files

## Fig 1_BCDEFG/fig1BCD
- directory name "ab0" denotes parameter value α + β=0, "ab1" denotes parameter value α + β=1, "abm1" denotes parameter value α + β=-1
- l.txt files contain structure size evolution from Gillespie simulation written as: \
    time | size of structure 1 | size of structure 2 | ... | size of structure n | subunit pool size
- t_xyz.txt files contain structure size evolution from ODE solution written as: \
    time | size of structure 1 | size of structure 2 | ... | size of structure n
- analysis.m contains MATLAB codes for data analysis. \
**( analysis codes are of basic nature and do not produce figures as presented in the study)**

## Fig 1_BCDEFG/fig1EFG
- file name "ab0.txt" denotes parameter value α + β=0, "ab1.txt" denotes parameter value α + β=1, "abc1_1.txt" and "abc1_2.txt" denote parameter value α + β=1 for two competeing structures 1 and 2 respectively.
- above described files contain structure size evolution from Gillespie simulation written as: \
    time | size of structure 1 | size of structure 2 | ... | size of structure n | subunit pool size
- fig1EF.nb contains MATHEMATICA codes for data analysis. \
**( analysis codes are of basic nature and do not produce figures as presented in the study)**
