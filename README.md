author="Dominik G Grimm"
year=2011-2016

*********************
CEasyGWAS Framework
*********************

1.) Install Dependencies
------------------------

- Install SWIG: http://www.swig.org/download.html
- Install SCONS by typing in the following lines into the terminal
  $:> sudo pip install --egg scons



2.) Compiling the Code
----------------------

2.1) Compile C++ API and Binaries Only
**************************************

To compile the code you have to go to the root directory of the Framework and type:

$>: scons -j 4 --build=release

This command builds the code using 4 CPUs and the release command uses optimization techniques to make the code faster.


2.2) Compile C++ API and Python Interfaces
******************************************

To compile the C/C++ code and build the python interfaces, SWIG has to be installed. To compile the interface you have to type:

$>: scons -j 4 --build=release --interface=python

