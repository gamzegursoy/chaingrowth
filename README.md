dynamic resampling usage
-----------------------------
-----------------------------

command below will create a 1000 chains, each name will start with AA. output file will contain the log of the weight of the chain and the (x,y,z) coordinates of each persistence unit. The parameters persistence length, fiber diamater (collision length), number of nodes diameter of the confinement can be changed using the resampling.ensemble.ini

./dynamic_resampling -conf dynamic.resampling.ensemble.ini -prefix AA -samplesize 1



resampling usage
-----------------------------
-----------------------------

command below will create a 1000 chains, each name will start with AA.
output file will contain the log of the weight of the chain and the (x,y,z) coordinates
of each persistence unit.
The parameters persistence length, fiber diamater (collision length), number of nodes
diameter of the confinement can be changed using the resampling.ensemble.ini

./resampling -conf resampling.ensemble.ini -prefix AA -samplesize 1
