# 6DOF_hexa-rotor
PX4 firmware modification to control a fully actuated hexa-rotor UAV


In order to use this modified codes it is necessary to replace these files in their respective PX4 firmware location, the main modules are located in the folder direction src/modules/

## Software In The Loop simulation
To test the modified code in the simulation environment, refer to the SITL simulation documentation of PX4 autopilot in https://docs.px4.io/v1.12/en/simulation/gazebo.html

## Real test firmware compilation
For a real test of the tilted multi-rotor UAV is is required to build and upload the modified firmware to the autopilot, for this two steps refere to https://docs.px4.io/master/en/dev_setup/building_px4.html

The following steps must be done to correctly implement the modified firmware

1. Replace the module files given in this repository into their respective modules in the original PX4 firmware
2. Build the firmware
3. 
