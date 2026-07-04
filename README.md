# Bondtech INDX Monolith gantry integration
This is a repository of various mods to make the Bondtech INDX toolchanging system compatible with the Monolith gantry and add features to it.

My modifications are based either off of the official reference models from Bondtech https://github.com/BondtechAB/INDX for the toolhead, or Monolith for the gantry parts: https://github.com/Monolith3D/Monolith_Gantry

Since every printer is different I have organised this repository with modularity in mind, here is soem general information, you will find more detailed information or hardware BOM'S in the relevant folders.

# IMPORTANT
 
I have noticed an issue with the toolbar spacing in teh 2wd CAD, it is about 6mm too far away from the toolhead, so do not print any parts for now. I will fix this asap, as long as this comment is here assume the issue is still there.

# 0 - Unchanged INDX reference parts
You do not need to print any parts from this folder, the contents are only there as reference if you want to make a CAD model for your specific configuration. These are the parts of the INDX toolhead that are not modified, everything here is included when you order the toolhead.

# 1 - Belt clamp
This is the belt clamp connecting the x carriage, the belts and the toolhead.
In case you want to use a nozzle camera choose the appropriate sub folder as the mount for those is integrated into this part.

You only need the contents of one sub folder.

# 2 - Scanning probe mount
This is an attachment for various scanning Z probes.
It is not strictly necessary as the INDX Toolhead already has a integrated loadcell as a Z-probe, but scanning Z probes like the various versions of beacon and cartographer or the one from Bondtech specifically intended for the INDX system still provide a significant quality of life benefit, like rapid bed meshing. 

The mounts also have a mount for a X endstop integrated and provide adittional support to the nozzle cam if you choose that option.

You only need the contents of the one sub folder for your specific probe, if you do not use any scannign probe you do not need any of these mounts.

# 3 - Cooling ducts
These are the cooling duct options. They are specifically designed to not decrease the minimum distance between tools and not impact xy travel.
You can still choose to go with the official Bondtech ducts, however be aware that they increase the minimum tool to tool distance from ~34mm to ~40mm
You can find the bondtech ducts here: https://github.com/BondtechAB/INDX/tree/main/CAD/STL
If you do decide to go with them, you do not need anything from this folder, otherwise you only need the contents of one sub folder.

# 4 - Tool holders
These are various options for the front 1515 beam on which the tools are mounted.
You will find more information in the readme in the folder, but once again you only need the contents of one sub folder

# 5 - Miscellaneous
Lastly "the other stuff", basically optional or quality of life parts that do not fit in the other categories, check the readme in the folder for more details.

# future plans:

No protrusion versiopns fo the toolbar, so that it is also compatible with stock 2020 Voron frames and panels

6mm belt compatibility

# Licenses
Because Monolith3d and Bondtech use different licenses there is no overarching license for this entire project.
Instead you will find the relevant licenses in the folders dependiong on from where I got the original parts I modified.
If that is an issue in some way please contact me.

# contact
If you have questions, feature requests or notice any issues feel free to contact me.
Eiter via email at alx.3dp@gmail.com, @ me in the Bondtech discord server, the project thread in the Monolith discord server or just write me a DM to alx1234