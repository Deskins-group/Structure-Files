Different VASP input and output files are provided for our simulations of MXenes.

- Geometry-Optimization.tar.gz - contains input and output files for optimizing the MXene geometries. CONTCAR files of all the optimized geometries are also provided. 

- BaderCharge_Ti3C2O2.tar.gz - contains essential input (INCAR, KPOINTS, POTCAR, POSCAR) and output (OUTCAR, CONTCAR, OZICAR) files for Bader charge calculations. The POSCAR file was taken from the outputs of PBE geometry optimization calculations. The resulting Bader charges are also given, in 'BaderCharges.txt'. No pre-processing is required before job submission. Post-processing code and instructions for Bader charge analysis from the Henkelman Group can be found here: https://theory.cm.utexas.edu/henkelman/code/bader/

- DOS_PBE_Ti3C2O2.tar.gz - contains essential input (INCAR, KPOINTS, POTCAR, POSCAR, CHGCAR) and output (OUTCAR, CONTCAR, OZICAR, DOSCAR) files for DOS calculations with the PBE functional. The POSCAR and  CHGCAR files were taken from the outputs of PBE geometry optimization calculations.. No pre-processing is required before job submission. Post-processing was done using VASPKIT, and instructions can be found here: https://vaspkit.com/tutorials.html#density-of-states

- DOS_HSE06_Ti3C2O2.tar.gz - contains essential input (INCAR, KPOINTS, POTCAR, POSCAR, CHGCAR) and output (OUTCAR, CONTCAR, OZICAR, DOSCAR) files for DOS calculations with the HSE06 functional. The POSCAR, WAVECAR, and CHGCAR files were taken from the outputs of PBE geometry optimization calculations. No pre-processing is required before job submission. Post-processing was done using VASPKIT, and instructions can be found here: https://vaspkit.com/tutorials.html#density-of-states

- WorkFunction_Ti3C2O2.tar.gz - contains essential input (INCAR, KPOINTS, POTCAR, POSCAR, CHGCAR) and output (OUTCAR, CONTCAR, OZICAR, LOCPOT) files for work function calculations. The POSCAR, WAVECAR, and CHGCAR files were taken from the outputs of PBE geometry optimization calculations. No pre-processing is required before job submission. Post-processing was done using VASPKIT, and instructions can be found here: https://vaspkit.com/tutorials.html#potential-related

- MechanicalProperties_Ti3C2O2.tar.gz - contains all files and directories included in the calculation of elastic coefficients C11 and C12, Young's modulus, bulk modulus, shear modulus, and Poisson's ratio. Pre- and post-processing were done using VASPKIT, and instructions can be found here: https://vaspkit.com/tutorials.html#mechanical-properties

