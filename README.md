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

relative e steps should also be enabled

anything that changes the order that perimeters print in should be disabled. 

oh... and turn off retraction for now (sorry)

z-seam aligned. (just to reduce variables that would break the output gcode)

Any layer height is now acceptable. Remember to set the layer height in the coresponding input field. (really should just grab it out of the gcode.)

An extrusion multiplier field is now functional. This ONLY affects the raised perimeters, and is not applied to top or bottom perimeters.

Even number of perimeters.

the code skips the first layer to allow for a thicker first layer.

copy gcode into the text area on the left, click process, copy the new gcode from text area on the right.

A discord channel to discuss this concept on.
https://discord.gg/6sPey3wW47

Have fun,
Bryan MacLee
![20220811_073823](https://user-images.githubusercontent.com/100145297/184260325-b141dcc3-35cd-484b-840d-d9b4857a2443.jpg)
![interlockingLayers v2](https://user-images.githubusercontent.com/100145297/184260344-1f29f45f-9044-4813-aad1-9e5edc438fd3.png)
