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

oh... and turn off retraction for now (sorry)

currently, only 0.2 layer heights and 4 perimeters. (I know, not very capable, im working on it)

copy gcode into the text area on the left, click doit, copy the new gcode from text area on the right.

A discord channel to discuss this concept on.
https://discord.gg/6sPey3wW47

Have fun,
Bryan MacLee
![20220811_073823](https://user-images.githubusercontent.com/100145297/184260325-b141dcc3-35cd-484b-840d-d9b4857a2443.jpg)
![interlockingLayers v2](https://user-images.githubusercontent.com/100145297/184260344-1f29f45f-9044-4813-aad1-9e5edc438fd3.png)
