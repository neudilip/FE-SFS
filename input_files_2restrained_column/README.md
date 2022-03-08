#  Restrained column exposed to fire: FE-SFS

This input file consists of following input codes

-input_beam_buckle.fil    			Abaqus result fil file after buckling analysis using beam  element which used in strucutral_beam.inp

-input_beam_buckle.odb    			Abaqus result odb file after buckling analysis using beam  element which used in strucutral_beam.inp

-input_structural_shell_buckle.fil    		Abaqus result fil file after buckling analysis using shell  element which used in strucutral_beam.inp

-input_beam_buckle.odb    			Abaqus result odb file after buckling analysis using beam  element used in strucutral_beam.inp

-restrained_column_mat_temp.py    		A python script to generate material data and fire temeprature data used for strucutral analysis

-structural_beam.inp    			Abaqus input file to perform structural analysis for restrained column using beam element

-structural_beam_buckle.inp    			Abaqus input file to perform linear buckling analysis for restrained column using beam element

-structural_shell.inp    			Abaqus input file to perform structural analysis for restrained column using shell element

-structural_shell_buckle.inp    		Abaqus input file to perform linear buckling analysis for restrained column using shell element


Note: Run the simulation using this file location as working direction
Note: To run the above python scripts, the current modal name in Abaqus/CAE must be Model-1
