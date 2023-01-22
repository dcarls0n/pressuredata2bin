# pressuredata2bin
C++ executable which compresses large pressure tensor data files output from LAMMPS from ASCII encoded text files to a space-efficient binary file. Used to post-process pressure tensor data for Green-Kubo viscosity estimation from molecular dynamics simulations.

This tool is used to save storage space after a completed LAMMPS simulation and to prepare the binary file required by the "autocorrelation_multithreaded" software tool, which uses the binary output of this tool to calculate the autocorrelation function of the pressure tensor elements.
