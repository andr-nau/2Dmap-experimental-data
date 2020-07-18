# 2Dmap-experimental-data
The task was to build 2D color map from experimental dataset. Changing parameters are: external magnetic field,
testing signal (called "level"), and sample response - electrical current (called "switching current").

The experiment is about vortices movement in superconductor material, affected by magnetic field.

__INPUT:__

I have set of experimental data files: 

- S-curve168.txt 
- ...
- S-curve468.txt.

Each file corresponds to the specific magnetic field applied during the measurement (fields set: 7 -> 10 milli-Tesla, step 0.01).

Files contain 2 columns: changing parameter (level) and response of the sample (critical current).

__OUTPUT:__

2D map: X: level, Y: magnetic field, Z: switching current.


![Output figure](https://github.com/andr-nau/2Dmap-vortex-experiment/blob/master/Final_2Dmap.png "Sample result")

Trianlge features are the signs of vortex movement in the sample during the changes of magnetic field and "level" signal, applied to the sample.
