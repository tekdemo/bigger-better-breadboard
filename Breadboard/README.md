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

Part List
-------

quantity| Description 			| Link
-------:|-------------------------------|------
12 	| 3/4"-1" standoffs     	|
12 	| 3/4"-1" length bolts  	|
12 	| nuts                  	|
21"	| non-insulated bus wire 	| [Radio Shack](https://www.radioshack.com/pretinned-solid-bus-wire-24awg/2781341.html)
Lots| Solder					|
2  	| 15.5"x18" plates      	|
15 	| Blue banana plug, female 	| [Digikey](http://www.digikey.com/product-detail/en/108-0910-001/J155-ND/5933)	
15 	| Red banana jack, female 	| [Digikey](http://www.digikey.com/product-detail/en/108-0902-001/J151-ND/5929)
150	| Black banana jack, female 	| [Digikey](http://www.digikey.com/product-search/en/connectors-interconnects/banana-and-tip-connectors-jacks-plugs/1441927?k=J152-ND)
~30	| Purple Banana Plugs, male 	| [Digikey](http://www.digikey.com/product-search/en?vendor=0&keywords=j345-ND)

The male plug quantity will vary depending on the number of components and jumpers 
you intend to make. It's also very handy to have some red and blue male plugs for the power
supply leads. For ICs, you also might consider colored plugs to indicate Power and Ground pins.

Known Issues
------------
- Mounting holes may be missing from some files, and need to be to the deisgn or manually drilled.