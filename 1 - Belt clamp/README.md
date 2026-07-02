# Belt clamp

The Belt clap design is based off of the official Monolith belt clamp you can find here: https://github.com/Monolith3D/MISC/tree/main/Monolith_SLM_belt_clamps

I redesigned it a little to make it compatible with the INDX toolhead, it allows up to 12mm wide belts.
I would recommend using the strongest material you can for this part since the walls of the screw holes need to be quite thin due to the way the toolhead is designed, I personally use annealed pet-gf.

To reach higher belt tensions that increase imput shaper performance and therefor maximum usable acelleration I highly recommend using a pretensioner to tension and fix the belts in place when installing the belt clamp, best ask in teh Monolith discord and someone will probably be able to point you towards one, I will make my own design at some point as well.  

If you want to use a Nozzle camera you need to choose the appropriate folder since the camera mount is integrated into the belt clamp.



# BOM
No matter which version you choose, you will need: 

4 m3x6 FHCS screws | these screws are used to attach the beltclamp to the MGN12 carriage and to secure the  belts to the belt clamp prior to installing the actual toolhead using the belt clamp plate.

The Screws to mount the actual toolhead to the Belt clamp will be added once I have received th toolhead and verified the lengths. If this is still here after the 19th of July 2026 I ahev forgot so please contact me to remind me...

Nozzle cam specific BOM:

2 m3x8-10 screws | used to secure the nozzle cam mounting parts 


# Nozzle cam
I use a cheap camera module from Ali express and that is what I modeled the camera mount after, so no guarantees it will fit.

It is designed to be used with 2 small rbg leds I had from my XOL toolhead, you can find them here:
https://www.replimat.eu/4x-rgbw-sequins-for-xol-minisb/rt10179
You can probably find them elsewhere as well.
If you want another lighting option contact me and I will see what I can do though the space is very limited.

The 3DO nozzle cam V2 is not compatibel with the current mount since it uses a custom sensor mounting pcb and I havent yet bothered to design something for it. If you want to use this, either make your own mount (and please send me the step file so that I can add it here) or contact me and i will see if I can make it, the contact details are in the main readme.

The original 3DO nozzle cam (non V2) *probably* works, as should most others that are just the small camera module mounted on a ribbon cable, but no guarantees.
