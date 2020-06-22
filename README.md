# 2Dmap-experimental-data
2D map of experimental dataset (vortices in superconductor affected by magnetic field)

INPUT:

There is set of experimental data files: 

- S-curve168.txt 
- ...
- S-curve468.txt.

Each file corresponds to the specific magnetic field applied during the measurement (fields set: 7 - 10 mT, step 0.01 mT).

File contains 2 columns: changing parameter (level) and response of the sample (critical current).

OUTPUT:

__2D map: X: level, Y: magnetic field, Z: current__

![Output figure](https://github.com/andr-nau/2Dmap-vortex-experiment/blob/master/Final_2Dmap.png "Sample result")

Trianlge features are the signs of vortex movement in the sample during the changes of magnetic field and special "level" signal, applied to the sample.
