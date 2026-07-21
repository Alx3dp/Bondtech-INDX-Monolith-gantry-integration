# Scanning Z probe mounts

Important: Cartographer V3 and beacon revD only is compatible with the mounts with Nozzle cam in the right angle configuration while Beacon revH is only compatible with it in the regular configuration, not the low profile one.
If you have the regular or low profile versions you need to resolder it to be right angle.
However he regular version definitly works with the no nozzle cam mount, the low profile one might but you will need to bend the wires quite sharply.

As of right now there are only options for the Beacon and Cartographer probes, I am planning to make a version for the INDX custom one but will wait until it is released so that I can confirm dimensions of it.

The Beacon/cartographer mounts should be compatible with all versions of these probes that have the cables going upwards, so the low profile versions are not compatible.

If you have a different probe you wish to use contact me and I will see what I can do, contact details are in the main readme.

# BOM

All versions:
2 m3x5x4 Heat set inserts |  same as what Voron and most others use, used to mount the z probe

2 m3x4-6 screws | used to mount the Z probe

d2f or similar microswitch | This is used for the X endstop, if you use another endstop or sensorless homing you do not need this

2 m2x8-10 self tapping screws | Used to mount the microwsitch

Additionally for the versions with nozzle camera:
2 m3x5x4 Heat set inserts |  used for the nozzle cam mount

# probe offsets

Beacon/carto without nozzle cam:
X: -38 mm
Y: 0mm

Beacon/carto with nozzle cam:
X: -48 mm
Y: 0mm
