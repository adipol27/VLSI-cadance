In this exercise we created a circuit design - MUX4to1 withe several requirements:
	• Multiplexer with 4 inputs, 2 select inputs and one 	output.
	• Use only standard CMOS cells (INV, NOR, NAND, XOR, 	AOI…) from	gsclib090. Notice different cell sizes and 	topology.
	• Rise/fall/delay time less than 75ps in worst case 	scenario.
• Use 4 similar multiplexers as load for simulation.
	• Use 1.2V supply voltage. 
We Created schematic view in Virtuoso, symbol view,test circuit and run ADE simulation. 
We Created the Layout in Cadence Virtuoso and kept the requirements:
	• Use M1 – M4 for interconnections.
	• Make the layout dense as possible. Remember area = 	money.
	• Input/output pins have to be on highest used metal.
We Ran LVS, DRC and Quantus QRC to create extraction.
