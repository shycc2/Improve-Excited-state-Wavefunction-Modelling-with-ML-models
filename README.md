# Improve-Excited-state-Wavefunction-Modelling-with-ML-models

1.Reference geometry
  
  The reference geometry folder includes the results of the equilibrium position from CASSCF method and files we used to carry out CASSCF calculation.
  
  The sys1_cas.log and sys1_reference.xyz is produced by CASSCF module in OpenMolcas package
  
  system1.xyz is the cartesian coordination file of 1,2-di(3-furyl)ethene before optimisation.
  
  job.pbs and sys1_cas.input is the script for running the CASSCF calculation.
   
2.Sampling geometry
 
  The sampling geometry folder is used to generate new geometries of 1,2-di(3-furyl)ethene around the reference geometry 
  
  Read_log is used to extract information from log file produced by CASSCF calculation.
  
  Genarate_new_xyz_files is used to calculate new geometries and put the new cartesian coordinate files into a new folder.

3.Machine learning model
  
  The machine learning model folder includes how we build up and train our model
  
  Some part of the model setup is based on the architechture from Ruard's work[1].



[1]R. V. Worknum, J. P. Malhado, P. Marquetand, *CASNet: Learning Complete Active Space Orbitals using Message Passing Neural Networks*, 2023, Available at https://github.com/rhjvanworkum/CasNet: https://github.com/citation-stylelanguage/styles/blob/master/cellular-and-molecular-bioengineering.csl
   
