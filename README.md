# Interlocking-layers
A gcode post proccessor that interlocks perimeters vertically

DISCLAIMER:   I am NOT a programmer! I only know an ANCIENT version of javascript, and even that, my code is ugly, bloated, and practically unreadable.
              for all of this; I truly appologize.
              If this idea is found to warrent further investigation, a total redo (probobly by someone that knows what they are doing : ) will certainly
              be in order.
              
I have only tested this with prusa slicer v2.0.0 

Simple shapes extruded upward are recomended as there is currently no accounting for a perimeter being offset in XY from the corresponding perimeter below.
Multiple islands seems to work fine.

" ; change layer "    - should be added to the "before layer change" custom gcode

verbose output should be enabled

anything that changes the order that perimeters print in should be disabled.

currently, only 0.2 layer heights and 4 perimeters. (I know, not very capable, im working on it)

Have fun,
Bryan MacLee
