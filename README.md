# Drums

## Features
These modules features 6 individually triggered and tuned drum voices in one module. The code was written Jan Ostman. I have chosen to rehost the code here for other's convenience as Jan's hosting method introduced numerous endlines that prevented the code from compiling. Jan's source code can be found here:

[Western Drums, DSP-D8](https://janostman.wordpress.com/2016/01/03/the-dsp-d8-drumchip-source-code/)

[Latin Drums, DSP-L8](https://janostman.wordpress.com/2016/01/04/the-dsp-l8-latin-perc-source-code/)

## Files
### westernDrums_01.ino and latinDrums_01.ino
This is the Arduino code. An ISP header on the board allows the microcontroller to be programmed directly.

### drums_xx.brd and .sch
These are the Eagle files for the PCB. To order PCBs, gerbers need to be generated using a CAM job in Eagle. A free version of Eagle is available that can do this. Both the latin and western drums use the same board, the only difference is the panel and code.

### drumsParts_xx.md [Not Yet Complete]
This is the parts list. A Mouser BOM is available at in this file as well.

### westernDrums.ai and latinDrums.ai
This is the panel in Adobe Illustrator format. This can be used to manufacture a panel, which I do with 1/8" acrylic and a laser cutter.

## Updates
### 01 

##### 30JUL18

Verified design. All functions work, though two issues were found. Added values to Eagle files for resistors and capacitors. Updated .brd to fix ISP issue, though this is currently untested. All signals were rerouted.

##### 24JUN18
First push to GitHub. Currently this design is untested.