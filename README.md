This is an Open source code operating with an Open source license that comply with the Open Source Definition —. This code was initially builded to run under Ubuntu OS. This work was part of my master degree dissertation. As part of the developing and computation of bilayer graphene and bilayer nitrite boron electronic bands.

To compile these codes, you must at least had count with at least the following libraries:
 <cfloat>
 <cmath>
<armadillo>

The lattice we used in this code, was calculated manually and introduced into the library <lattice.h> Where you can find all the atomic coordinates of each atom. The system max size is determined by this library, 148 atoms per layer. With the aid of the commensuration theorem, you can specify the type of lattice you want.

How to use the code:
0. Use the commensuration theorem to determine an angle and a crystalline structure size. Code for this purpose can be founded in the folder Commensuration theorem.
1. Compile in the folder 1-unitcell to generate a file that creates the appropriated instructions (in the base of the commensuration theorem) to produce the band structure files.
2. Use the 2-band folder; you can get a code that creates band structures, close to Dirac points. Introducing the data generated in step 1, in the program located in the folder (2-band) folder,  generates the band structures. You can plot it and get the band structure around the Dirac points.  
3. Use the 3-hist folder; you can get a code that creates histograms of the band structures shown previously, evaluated on the Dirac cones. Introducing the data generated in step 1, 3-hist folder code generates the histogram of each band structure.  
 



