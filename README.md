KiCad files for the pcb in the `pcb/` directory

dxf files for the plates in the `plates/` directory. This includes files for the templates used to cut out the wrist rests.

Most of the components needed for assembly should be properly labelled in the pcb files. The screen used is [this adafruit one](https://www.adafruit.com/product/931) based on the SSD1306 driver chip.

You'll also need M2 standoffs of various lengths to separate the two plates enough to fit the PCB. I think around 12mm is the minimum allowable height.

Firmware source uses QMK and can be found [here](https://github.com/csun/ellipsis_split_firmware)
