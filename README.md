# Smalltalk-Interpreter

This is a light-weight interpreter written in GNU Smalltalk for the BASIC language (which was designed by by John G. Kemeny and Thomas E. Kurtz, released at Dartmouth College in 1964). 

This interpreter was implemented as an assignment for Wesley Mackey's Winter offering of CSE112 (Comparative Programming Languages) at the University of California, Santa Cruz. 

I collaborated with my close colleague [Nicholas Brown](https://github.com/Nickb53) on this interpreter, with both of us contributing equally to it's contents.

### How do I run this? 

Firstly, any `.mb` file must be translated to an intermediate `.mbst` file, using the Perl program `mb2mbst.perl` located in this repository. As you can see, some sample `.mbst` programs are already available in this repository. 

Run `./mbint.st [file.mbst]` to begin interpretting! 


