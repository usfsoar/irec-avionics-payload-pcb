# IREC Avionics Payload PCB

This is the PCB for the payload of USF Society of Aeronautics and Rocketry's 2019 IREC rocket. The PCB is made in KiCad (pronounced key-cad). The different files are split into the folders ***payload_ground_pcb*** and ***payload_main_pcb*** under those there are the files:

* ***avionics-*.pro*** - This is the base project which you should open in KiCad.
* ***avionics-*.sch*** - This is the sketch of the PCB and shows which components should be connected where.
* ***avionics-*.kicad_pcb*** - This is the actual PCB that has the components laid out and connected with physical dimensions.
* ***components*** - This folder contains components that are not by default included with KiCad

## About the board

The main components of the board are:

* [Teensy 4.0](https://www.pjrc.com/store/teensy40.html) - This small Arduino compatible board is very powerful for its size with 600 MHz, 1M RAM, and 2M Flash as well as lots of connectivity options.
* [MS5607](https://www.te.com/commerce/DocumentDelivery/DDEController?Action=showdoc&DocId=Data+Sheet%7FMS5607-02BA03%7FB2%7Fpdf%7FEnglish%7FENG_DS_MS5607-02BA03_B2.pdf%7FCAT-BLPS0035) - This is the barometric sensor for the board, it provides high resolution and low pressure while being inexpensive and having a digital interface.
* [ADXL357](https://www.analog.com/media/en/technical-documentation/data-sheets/ADXL356-357.pdf) - This is the accelerometer that provides +-40g while having high sensitivity, low noise, and a digital interface.
* [SAM M8Q](https://www.u-blox.com/sites/default/files/SAM-M8Q_DataSheet_%28UBX-16012619%29.pdf) - This is the GPS module and it provides a built in antenna and a digital interface.
* [RFM95W](https://cdn.sparkfun.com/assets/learn_tutorials/8/0/4/RFM95_96_97_98W.pdf) - For now this is a temporary RF module that will stand in for what ever RF solution is decided while testing. It provides many benefits for this purpose such as being in the 915MHz range and having long enough range that if necessary it could be used for launch.

## How to contribute

KiCad is a free and open source software that is available on most desktop OSs. To learn how to use KiCad [here](https://github.com/MalphasWats/hawk) is a pretty great tutorial that goes through making a simple PCB. You can go at your own pace but it should take about an hour but after that you should have a pretty good understanding of KiCad.

If you want to add-on to the board the best way would be to create a hierarchical sheet if you are adding on a new subsystem or if you are adjusting the main board try not to adjust (move, rename, etc) items that you do not plan to change.

## Pictures

![Schematic](https://raw.githubusercontent.com/usfsoar/irec-avionics-payload-pcb/master/avionics-payload-schematic.jpg)

![PCB](https://raw.githubusercontent.com/usfsoar/irec-avionics-payload-pcb/master/avionics-payload-pcb.jpg)
