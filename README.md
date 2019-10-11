# IREC Avonics Payload PCB

This is the PCB for the payload of USF Society of Aeronautics and Rocketry's 2019 IREC rocket. The PCB is made in [KiCad](http://www.kicad-pcb.org/) (pronounced key-cad). The diffrent files are:

* avionics-payload.pro - This is the base project which you should open in KiCad.
* avionics-payload.sch - This is the sketch of the PCB and shows which commponents should be connected where.
* avionics-payload.kicad_pcb - This is the actual PCB that has the components layed out and connected with physical dimentions.
* components - This folder contains components that are not by default included with KiCad

## How to contribute

[KiCad](http://www.kicad-pcb.org/) is a free and opensource software that is avaiable on most desktop OSs. To learn how to use KiCad [here](https://github.com/MalphasWats/hawk) is a good tutorial that takes you throught all the steps of making a full board.

If you want to add-on to the board the best way would be to create a hierachical sheet if you are adding on a new subsystem or if you are adjusting the main board try not to adjust (move, rename, etc) items that you do not plan to change.
