# Repository Information:
This repository stores the data used in the manuscript [Size regulation of multiple organelles competing for a shared subunit pool](https://doi.org/10.1101/2020.01.11.902783).

# Description of the data files for main text:

## Fig 1BCDEFG/fig1BCD
- directory name "ab0" denotes parameter value α + β=0, "ab1" denotes parameter value α + β=1, "abm1" denotes parameter value α + β=-1
- l.txt files contain structure size evolution from Gillespie simulation written as: \
    time | size of structure 1 | size of structure 2 | ... | size of structure n | subunit pool size
- t_xyz.txt files contain structure size evolution from ODE solution written as: \
    time | size of structure 1 | size of structure 2 | ... | size of structure n
- analysis.m contains MATLAB codes for data analysis. \
**( analysis codes are of basic nature and do not produce figures as presented in the study)**

## Fig 1BCDEFG/fig1EFG
- file name "ab0.txt" denotes parameter value α + β=0, "ab1.txt" denotes parameter value α + β=1, "abc1_1.txt" and "abc1_2.txt" denote parameter value α + β=1 for two competeing structures 1 and 2 respectively.
- above described files contain structure size evolution from Gillespie simulation written as: \
    time | size of structure 1 | size of structure 2 | ... | size of structure n | subunit pool size
- fig1EF.nb contains MATHEMATICA codes for data analysis. \
**( analysis codes are of basic nature and do not produce figures as presented in the study)**

## Fig 2B
- In the filemanes L_nf_*.txt, the number denotes number of flagella in the cell
- L_nf_*.txt files contain flagella size evolution from Gillespie simulation written as: \
    time | size of flagellum 1 | size of flagellum 2 | ... | size of flagellum n | subunit pool size
    
## Fig 2C
- In the filemanes L_intact and L_cut denotes the flagellum that was intact and cut in a "long-zero" experiment respectively.
- L.txt file contains flagella size evolution from Gillespie simulation written as: \
    time | size of flagellum 1 | size of flagellum 2 | ... | size of flagellum n | subunit pool size \
- L_intact.txt and L_cut.txt files contain flagella size evolution from long-zero experiment written as: \
    time | size of flagellum \
- analysis.m contains MATLAB codes for data analysis. \
**( analysis codes are of basic nature and do not produce figures as presented in the study)**

## Fig 3B
- The files llps.txt and localized_assembly.txt contain centrosome size evolution from Gillespie simulation where they grow accordingly 
- Data in the files written as: \
    time | size of centrosome 1 | size of centrosome 2 | ... | size of centrosome n | subunit pool size

## Fig 3C
- The files l_*.txt contain centrosome size evolution from Gillespie simulation. The number in filename denotes number of centrosomes growing in the system/cell
- Data in the files written as: \
    time | size of centrosome 1 | size of centrosome 2 | ... | size of centrosome n | subunit pool size
- Experimental data is stored in directories "exp1" and "exp2". The filenames contain number of centrosome growing in the system/cell
- The files contain single column data of mean size of centrosomes for many such experiments.
- analysis.m contains MATLAB codes for data analysis. \
**( analysis codes are of basic nature and do not produce figures as presented in the study)**

## Fig 3C_inset
- The files l_*.txt contain centrosome size evolution from Gillespie simulation. The number in filename denotes volume of the system/cell
- Data in the files written as: \
    time | size of centrosome 1 | size of centrosome 2 | ... | size of centrosome n | subunit pool size
- Experimental data is stored in the file "V_cell_centro.txt". The file contains: \
  Cell/system size | average centrosome size | standard error in size
- analysis.m contains MATLAB codes for data analysis. \
**( analysis codes are of basic nature and do not produce figures as presented in the study)**

## Fig 3D
- The file l.txt contains centrosome size evolution from Gillespie simulation where they grow from two components/subunits 
- Data in the file is written as: \
    time | size of centrosome 1 | size of centrosome 2 | ... | size of centrosome n | subunit 1 pool size | subunit 2 pool size
    
## Fig 4B
- The file l.txt contains microtubule(MT) filament size evolution from Gillespie simulation
- Data in the file is written as: \
    time | size of MT 1 | size of MT 2 | ... | size of MT n 
- The file nr.txt contains nucleus size (in radius) evolution from the same Gillespie simulation
- Data in the file is written as: \
    time | size of nucleus 1 | size of nucleus 2 | ... | size of nucleus n
- analysis.m contains MATLAB codes for data analysis. \
**( analysis codes are of basic nature and do not produce figures as presented in the study)**

## Fig 4B_inset
- The directory number/name indicates the number of nuclei present in the system. Each directory contins a corresponding nr.txt file. 
- The file nr.txt contains nucleus size (in radius) evolution from the Gillespie simulation
- Data in the file is written as: \
    time | size of nucleus 1 | size of nucleus 2 | ... | size of nucleus n
- the directory "exp" contain experimental data.
- The files are numbered as nucleus number in system (i.e., 50.txt for 50 nuclei in the system). Each file contains average (over the nuclei) nucleus size in steady state. The data in the file: \
  time | nucleus diameter
- np_Rn.txt contains the steady state average (time) size of nucleii calculated using the above described files.
- The data is written as: \
  nuclei number | average nucleus size | standard error
- analysis.m contains MATLAB codes for data analysis. \
**( analysis codes are of basic nature and do not produce figures as presented in the study)**

## Fig 4C
- The directory named "data" contains files for nucleus size evolution obtained from Gillespie simulation. The files are named nr_*.txt with number denoting the system size (as radius of cylindrical system).
- Each file nr_*.txt contains nucleus size (in radius) evolution from the Gillespie simulation
- Data in the file is written as: \
    time | size of nucleus 1 | size of nucleus 2 | ... | size of nucleus n
- logR_logRn.txt file contains experimental data. The data is written as: \
  Log(system size) | Log(Renormalized nucleus size)
- analysis_all.m contains MATLAB codes for data analysis. \
**( analysis codes are of basic nature and do not produce figures as presented in the study)**

## Fig 4D
- The directory named "NEVD" and "NVVD" contain files for nucleus size evolution obtained from Gillespie simulation with growth from surface assembly and volume assembly respectively. Each directory contains nr_*.txt files. The number in the filename denoting the system size (as radius of spherical system).
- Each file nr_*.txt contains nucleus size (in radius) evolution obtained from the Gillespie simulation
- Data in the file is written as: \
    time | size of nucleus 1 | size of nucleus 2 | ... | size of nucleus n
- vcvn.txt file contains experimental data. The data is written as: \
  Sytem/Cell volume | Nucleus size (volume)
- analysis_all.m contains MATLAB codes for data analysis. \
**( analysis codes are of basic nature and do not produce figures as presented in the study)**

## Fig 5ABC
- The directory contains files "a.txt", "b.txt" and "c.txt" for the panels A, B and C.
- Each file contains structure size evolution from Gillespie simulation written as: \
    time | size of structure 1 | size of structure 2 | ... | size of structure n | subunit pool size
- Here a single structure was grown. Hence the other structure (third column) is at zero size.
- analysis.m contains MATLAB codes for data analysis. \
**( analysis codes are of basic nature and do not produce figures as presented in the study)**

## Fig 5EF
- The directory contains files "b.txt" and "c.txt" for the panels E and F.
- Each file contains structure size evolution from Gillespie simulation written as: \
    time | size of structure 1 | size of structure 2 | ... | size of structure n | subunit pool size
- analysis.m contains MATLAB codes for data analysis. \
**( analysis codes are of basic nature and do not produce figures as presented in the study)**

## Fig 5G
- The directory contains file "N_tauR.txt"
- The file contains residence time (calculated from structure size evolution obtained from Gillespie simulation) data written as: \
   Total subunit pool size (N) | Residence time \
   

## Fig 5H
- The directory contains file "l.txt".
- The file contains structure size evolution from Gillespie simulation written as: \
    time | size of structure 1 | size of structure 2 | ... | size of structure n | subunit pool size


## Fig 5I
- The directory contains file "s_k_pd.txt".
- The file contains phase diagram data (based on structure size evolution from Gillespie simulation) written as: \
  parameter value α + β | parameter value κ | number (phase identity)
- Phase identity number takes values 1 (not growing), 2 (fat tailed distribution) or 3 (bimodal distribution)
    

# Description of the data files for supplementary:

## Appendix 3 Fig 1
-  The directory contains two sub-directories "D_0.01" and "D_1" corresponding to data for diffusion constant value 0.01 and 1.
-  Each directory D_* contain three sub-directories "ab0", "ab1" and "ab-1"
-  The number in the name denote parameter value, i.e., the name "ab0" denotes parameter value α + β=0.
-  The directories "ab0" and "ab1" contain data for panels A, B, C and D. The numbering of sub-directories inside "ab0" and "ab1" are according to the increasing run time (as shown in figure).
-  The file l.txt saves structure size data from Gillespie simulation, written as: \
   time | size of structure 1 | size of structure 2 | ... | size of structure n | subunit pool size
-  The files n_P1_N_50.txt and n_P2_N_50.txt store resulting size distribution (of structure 1 and 2 respectively) from Gillespie simulation, written as: \
   Size | Probability for that size
-  The directories "ab-1" contain data for panels E, F and G. The files l.txt and n_P_N.txt have data in similar format as described above.

## Appendix 6 Fig 1
- The directory contains sub-directories "theory" and "exp" for theory results from Gillespie simulation and experimental data.
- The theory directory contains data file with flagella size evolution written as: \
    time | size of structure 1 | size of structure 2 | ... | size of structure n | subunit pool size
- The exp directory contains data files (for each flagella) with flagella size evolution from long-zero experiment, written as: \
    time | size of flagella

## Appendix 10 Fig 1
- The directory contains sub-directories named according to the figure panels and store theory results from Gillespie simulation.
- Each directory (except H) contains data file l.txt with structure size evolution written as: \
    time | size of structure 1 | size of structure 2 | ... | size of structure n | subunit pool size
- directory "H" has three files "l10.txt", "l20.txt" and "l40.txt" containing data in same format as l.txt.

## Appendix 12 Fig 1
- The directory contains sub-directories named according to parameter values "alpha_plus_beta_0" and "alpha_plus_beta_1".
- "alpha_plus_beta_0" contains data for panels A, B and B-inset
- "alpha_plus_beta_1" contains data for panels C and D
- Each panel directory contains data file l.txt with structure size evolution obtained from Gillespie simulation, written as: \
    time | size of structure 1 | size of structure 2 | ... | size of structure n | subunit pool size


