# CSC 263/463 Assignment 2 - Xapian setup on CSUG
Referenced from Spring 2022  Assignment 2 instructions

## Installation instructions for CSUG
> - Login to any one of the CSUG Cycle machines (cycle1.csug.rochester.edu).
> - Download the file : `wget https://github.com/shaojiama/csc263_sp23_A2/raw/main/a2.tar.gz`
> - Unzip the file : `tar -xzvf a2.tar.gz`
> - `cd a2_xapian`
> - There is a sample file `a2.cpp`, you can use as the starter code.
  
## Compile & Run
> - use g++ to compile: `g++ -I./include/ -L./.libs/ -l xapian -o a2 a2.cpp`
> - the executable named `a2`.
  
## Submission
> - DO NOT submit the Xapian library, as it's too large.
> - You only need to submit your source code, e.g. `a2.cpp`, and the required report/plots.
