Unicode in Terminal
===================================

This project shows how to create a set of unit tests without a usage of any external framework.


To run tests:

1. Compile cpp modules to object files:
   `g++ -c *.cpp`
2. Compile  maintest file (and other cpp test modules if you have them in separate files):
   `cd test; g++ -c *.cpp`
3. Link all object files into executable testmain:
   `g++ -o testmain *.o ../*.o`
4. Run testmain:
   `./testmain`

