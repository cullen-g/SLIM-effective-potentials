# SLIM-effective-potentials
Code for visualizing the effective potentials of TW-SLIM instruments. The folder patxts/ contains potential arrays converted to txts using SLTools (and are quite large, managed using git lfs). Visualization.ipynb provides an example for a YZ (axial) view. The functionality for an XZ view exits, though only monomer patxt files are provided due to size constraints. 

To explore other SLIM potential settings:
1. Export a SLIM monomer or polymer to SIMION using pigsim
2. Run the pigsim lua file to generate the SIMION .iob
3. Fast Adust the ion bench to the desired field parameters for each set of electrodes (RF, Traveling Wave, and Guard), and export separately
4. Point the visualization.ipynb to these files


These research products were developed with the support of the NIGMS R01-GM140129, The examples provided are intended for research purposes only.
