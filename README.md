# CFD_DropletFormation

This code simulates droplet formation from a symmetric T-Junction using OpenFOAM (ver 1.7.1). It used interFOAM solver 
which works on VoF method.

To run simulation,

-> decomposePar <br />
-> mpirun -np 4 interFoam -parallel
