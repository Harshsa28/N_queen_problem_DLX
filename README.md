This is the code to solve the N Queen problem using Donald Knuth's Dancing Links and Algorithm X [DLX algorithm]

I used a generalized version of DLX Algorithm.

There are 2 types of columns: primary and secondary

Primary have to be covered exactly once [exact cover problem]

Secondary have to be covered at most once

To implement that, I have followed instructions in Knuth's paper by not adding secondary columns in the circular queue. 

This gives a very fast approach to N Queen problem.
