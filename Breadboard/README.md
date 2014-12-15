Bigger Better Breadboard 
================================
An obscenely large solution to several tiny problems.

Design Files
------------
The 2D design files for this were generated using Eagle CAD, because I had it handy. 

The SVG files were generated with eagle2svg, then edited with Inkscape and a CNC plugin to 
generate laser-cutter compatible paths. These hopefully will serve as a good starting point 
for generating your own breadboard with a laser cutter.

Please note that to reduce the file count and simplify design, the BRD files have layers that are 
disabled to generate specific SVG files. If you modify the design, you'll likely need to repeat this
process to generate the stencils. 


Assembly Guide
--------
_This will be updated later with additional details. Please file a bug report if something is unclear_

There's general idea for the assembly is to cut out a large board, jam a lot of connectors on it,
and mate it to the wires attached to the components. 

For the breadboard top, you want to select the `giant-breadboard_brd.svg` file. This contains 
the connector mounting hole pattern. 

For the bottom plate, you want to use the `giant-breadboard-with-engraving_brd.svg` file. This 
lets you clearly show the contacts and wires on the underside of the board, and really highlights
how a breadboard connects. 

For painting the top,  you can make masks using the `paint-stencil-positive.svg` and `paint-stencil-rows.svg` files. 

BOM
-------
_not yet availible: Please file a bug report if needed_


Known Issues
------------
- Mounting holes may be missing from some SVG files, and will need to be added or manually drilled.