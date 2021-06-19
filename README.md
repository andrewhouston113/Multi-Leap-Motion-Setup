# Multi-Leap-Motion-Setup
A sensor fusion pipeline to register and fuse the trajectories captured by multiple leap motion controllers.

This script will prepare multi-device Leap Motion data for comparison with a gold-standard motion capture setup.

The following steps will be performed: 

1) Sensor data will be read into the script. 
2) Sensor data will be cleaned using gap-filling and low-pass filtering. 
3) Sensor data will be orientated to a reference sensor using a Kabsch algorithm. 
4) Data fusion between sensor output will be performed, resulting in only one co-ordinate for each joint. 
5) Data will be stored in a C3D file, ready for quantification of kinematic outputs.
