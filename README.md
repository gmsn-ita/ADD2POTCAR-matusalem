# ADD2POTCAR-matusalem
Program to add to the POTCAR the self-energy potential, used in DFT-1/2 calculations.


BY FILIPE MATUSALEM, MARCH 2014     filipematus@gmail.com , based on add2POTCAR-eng.f90 by L F Guimaraes

Compile with: $g++ -o add2POTCAR-M add2POTCAR-v2.1.c

run the program entering the CUT value as argument. The program also accepts a second argument that changes the amplitude.

$add2POTCAR-M 3.81       #for CUT=3.81 and amplitude = 1

$add2POTCAR-M 3.81 -1       #for CUT=3.81 and amplitude = -1
