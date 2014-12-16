Irregularly Immense IC 
================================
A large breakout board for tiny chips

This is a breakout and protection board for DIP8 ICs. To encourage a wide variety of chips to be used, this board has a IO protection matrix on the bottom to help configure the chip's safety. Adjusting the pin matrix allows you to set the pin's usage mode between Power, Ground, Input, Output/IO, or Disconnected.
- Output/IO pins are then current limited using a resistor.
- Power and Ground pins are reverse polarity protected, and provided with bypass capacitors for stable operation of the IC. 
- Input pins are connected straight to the chip. 
- Disconnected pins are electrically isolated, if you're into that sort of thing.


Part List
---------

quantity        | Description 	        | Spec		    | Link
---------------:|-----------------------|---------------|------
1				|	DIP8 IC			 	|				| 
1, optional		|	DIP8 Socket	 		|				| 
0-8, as needed	|	Resistors			| 	 200 ohm    |
1				|	Capacitor	 		|	0.1uF-1uF	| 
2, suggested	|	Googly Eyes 	 	| 0.5" diameter	| 
1 				| N-Channel Mostfet   	| IRLML5103 S0T-23 or equivilent | [Digikey](http://www.digikey.com/product-detail/en/IRLML5103GTRPBF/IRLML5103GTRPBFCT-ND/2354248)
8 				| Purple Banana Plugs, male |	| [Digikey](http://www.digikey.com/product-search/en?vendor=0&keywords=j345-ND)
