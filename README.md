# ab-initio-methods
ab-initio methods for magnetic and spin-phonon coupling

This is a project for using WFU's high-performance computing cluster to study the ab-initio methods for magnetic and spin-phonon coupling. The code will open an input file (=.pipe) for a specific material that contains all necessary data information for the calculation, and run calculations based on the atom number(s) given, then it would create 6 different directories containing the updated pipe file according to each possible position(s) for the atom number. The code then will submit the tasks to the cluster automatically and run calculations for each atom. 
