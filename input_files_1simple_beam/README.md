# Simple beam exposed to fire: FE-SFS

This input file consists of following input codes

simple_beam_mat_temp.py    			A python script to generate material data and fire temeprature data used for strucutral analysis

2D_temp.inp    					Abaqus input file to perform thermal response analysis for simple beam ( 2D member cross-section)

structural_beam.inp    				Abaqus input file to perform structural analysis for restrained column using beam element



structural_shell.inp    			Abaqus input file to perform structural analysis for restrained column using shell element
						( in line 4040 of structural_shell.inp, add the location of temperature_shell.odb .i .e this folder location)

Note: Run the simulation using this file location as working direction
Note: To run the above python scripts, the current modal name in Abaqus/CAE must be Model-1
