### Artifact: `assignments.f90`

#### Description:
A Fortran 90 program to verify the following MILP assignment constraints in the conference article: (16), (24), (25), (26), and (27) as realized for the examples of Figures 2 & 3.

#### Requirements:
* a Fortran 90-compatible compiler, e.g. [gfortran](https://gcc.gnu.org/wiki/GFortran);
* at least version 3.10 of [CMake](https://cmake.org/).

#### Build and Run on *nix Systems:
* execute `ccmake .` where `assignments.f90` is located on your system, or replace `.` with the path to it if an out-of-source build is preferred, and select the desired Fotran compiler;
* configure by pressing `c` then generate the `makefile` by pressing `g`;
* build with `make`;
* run the generated `assignments` executable.

#### What to Expect:
A text output in the terminal that will verify the aforementioned equations and examples.

