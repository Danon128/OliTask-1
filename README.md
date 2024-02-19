# OliTask-1
## To run the code:
1. clone this respository
2. Make sure you have MinGW (gcc and g++ compilers) installed and paths set
3. Make sure you have CMake installed and path set
4. In project root create Build directory `mkdir Build`
5. Move to newly create directory `cd Build`
6. Generate Makefile: `cmake ../ -G"MinGW Makefiles`
7. Build the project: `cmake --build .`
8. OPTIONAL: Run the tests: `ctest`
9. Put file with input data `input.txt` into Build directory (example of input.txt provided below)
10. Run the code: `DLXSolver_run.exe`

### Example `input.txt`
9
0 0 0 0 3 7 6 0 0
0 0 0 6 0 0 0 9 0
0 0 8 0 0 0 0 0 4
0 9 0 0 0 0 0 0 1
6 0 0 0 0 0 0 0 9
3 0 0 0 0 0 0 4 0
7 0 0 0 0 0 8 0 0
0 1 0 0 0 9 0 0 0
0 0 2 5 4 0 0 0 0
