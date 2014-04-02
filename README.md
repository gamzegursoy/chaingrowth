Please download executables and configuration files from the releases tab.
------------------------------------------------------------------------------
------------------------------------------------------------------------------

dynamic resampling usage
-----------------------------


command below will create a 1000 chains, each name will start with AA. output file will contain the log of the weight of the chain and the (x,y,z) coordinates of each persistence unit. The parameters persistence length, fiber diameter (collision length), number of nodes and the diameter of the confinement can be changed using the resampling.ensemble.ini

./dynamic_resampling -conf dynamic.resampling.ensemble.ini -prefix AA -samplesize 1



resampling usage
-----------------------------


command below will create a 1000 chains, each name will start with AA.
output file will contain the log of the weight of the chain and the (x,y,z) coordinates
of each persistence unit.
The parameters persistence length, fiber diameter (collision length), number of nodes and the
diameter of the confinement can be changed using the resampling.ensemble.ini

./resampling -conf resampling.ensemble.ini -prefix AA -samplesize 1


contact probability and mean-square spatial distance
------------------------------------------------------

command below will create two files with extensions {chain_file}.c and {chain_file}.sq.  
<chain_file>.c contains the contact probability for each contour length and 
<chain_file>.sq contains the mean-square spatial distance for each contour length.
Dynamic resampling and resampling outputs are slightly different, we created binearies for 
both output.
Please note that each contact probability and mean-square spatial distance should be
weighted by the chain weight.

./CheckDistance_dyn_resampling {chain_file} {number_of_nodes}


./CheckDistance_resampling {chain_file} {number_of_nodes}



