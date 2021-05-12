# Repository Information
This repository stores the data used in the manuscript [Size regulation of multiple organelles competing for a shared subunit pool](https://doi.org/10.1101/2020.01.11.902783).

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

## Fig 2_B
- In the filemanes L_nf_*.txt, the number denotes number of flagella in the cell
- L_nf_*.txt files contain flagella size evolution from Gillespie simulation written as: \
    time | size of flagellum 1 | size of flagellum 2 | ... | size of flagellum n | subunit pool size
    
## Fig 2_C
- In the filemanes L_intact and L_cut denotes the flagellum that was intact and cut in a "long-zero" experiment respectively.
- L.txt file contains flagella size evolution from Gillespie simulation written as: \
    time | size of flagellum 1 | size of flagellum 2 | ... | size of flagellum n | subunit pool size \
- L_intact.txt and L_cut.txt files contain flagella size evolution from long-zero experiment written as: \
    time | size of flagellum \
- analysis.m contains MATLAB codes for data analysis. \
**( analysis codes are of basic nature and do not produce figures as presented in the study)**

## Fig 3_B
- The files llps.txt and localized_assembly.txt contain centrosome size evolution from Gillespie simulation where they grow accordingly 
- Data in the files written as: \
    time | size of centrosome 1 | size of centrosome 2 | ... | size of centrosome n | subunit pool size

## Fig 3_C
- The files l_*.txt contain centrosome size evolution from Gillespie simulation. The number in filename denotes number of centrosomes growing in the system/cell
- Data in the files written as: \
    time | size of centrosome 1 | size of centrosome 2 | ... | size of centrosome n | subunit pool size
- Experimental data is stored in directories "exp1" and "exp2". The filenames contain number of centrosome growing in the system/cell
- The files contain single column data of mean size of centrosomes for many such experiments.
- analysis.m contains MATLAB codes for data analysis. \
**( analysis codes are of basic nature and do not produce figures as presented in the study)**

## Fig 3_C_inset
- The files l_*.txt contain centrosome size evolution from Gillespie simulation. The number in filename denotes volume of the system/cell
- Data in the files written as: \
    time | size of centrosome 1 | size of centrosome 2 | ... | size of centrosome n | subunit pool size
- Experimental data is stored in the file "V_cell_centro.txt". The file contains: \
  Cell/system size | average centrosome size | standard error in size
- analysis.m contains MATLAB codes for data analysis. \
**( analysis codes are of basic nature and do not produce figures as presented in the study)**

## Fig 3_D
- The file l.txt contains centrosome size evolution from Gillespie simulation where they grow from two components/subunits 
- Data in the file is written as: \
    time | size of centrosome 1 | size of centrosome 2 | ... | size of centrosome n | subunit 1 pool size | subunit 2 pool size
    
## Fig 4_B
- The file l.txt contains microtubule(MT) filament size evolution from Gillespie simulation
- Data in the file is written as: \
    time | size of MT 1 | size of MT 2 | ... | size of MT n 
- The file nr.txt contains nucleus size (in radius) evolution from the same Gillespie simulation
- Data in the file is written as: \
    time | size of nucleus 1 | size of nucleus 2 | ... | size of nucleus n
- analysis.m contains MATLAB codes for data analysis. \
**( analysis codes are of basic nature and do not produce figures as presented in the study)**

## Fig 4_B_inset
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

## Fig 4_C
- The directory named "data" contains files for nucleus size evolution obtained from Gillespie simulation. The files are named nr_*.txt with number denoting the system size (as radius of cylindrical system).
- Each file nr_*.txt contains nucleus size (in radius) evolution from the Gillespie simulation
- Data in the file is written as: \
    time | size of nucleus 1 | size of nucleus 2 | ... | size of nucleus n
- logR_logRn.txt file contains experimental data. The data is written as: \
  Log(system size) | Log(Renormalized nucleus size)
- analysis_all.m contains MATLAB codes for data analysis. \
**( analysis codes are of basic nature and do not produce figures as presented in the study)**

## Fig 4_D
- The directory named "NEVD" and "NVVD" contain files for nucleus size evolution obtained from Gillespie simulation with growth from surface assembly and volume assembly respectively. Each directory contains nr_*.txt files. The number in the filename denoting the system size (as radius of spherical system).
- Each file nr_*.txt contains nucleus size (in radius) evolution obtained from the Gillespie simulation
- Data in the file is written as: \
    time | size of nucleus 1 | size of nucleus 2 | ... | size of nucleus n
- vcvn.txt file contains experimental data. The data is written as: \
  Sytem/Cell volume | Nucleus size (volume)
- analysis_all.m contains MATLAB codes for data analysis. \
**( analysis codes are of basic nature and do not produce figures as presented in the study)**








