# CSC 263/463 Assignment 2 - Xapian setup on CSUG
Referenced from Spring 2022  Assignment 2 instructions

## Installation instructions for CSUG
> - Log on to the cycle machines on the csug network (ssh -L <username> cycle1.csug.rochester.edu)
> - Download the file : `wget https://github.com/shaojiama/csc263_sp23_A2/raw/main/assignment_2.tar.gz`
> - Unzip the file : `tar -xzvf a2.tar.gz`
> - `cd a2_xapian`
> - There is a sample file `a2.cpp`, you should use that as the starter code
  
## Compiling
To compile your project
> - `g++ -o a2 -I./include/ -L./.libs/ -l xapian a2.cpp`

## Running your Code
> - After compiling, you will see a executable named `a2`. To run use : `./a2`
  
## Submission
> - You only need to submit the `a2.cpp` file
> - And the required pltos : https://www.cs.rochester.edu/u/fnargesi/courses/263/a2/handout/a2.html
