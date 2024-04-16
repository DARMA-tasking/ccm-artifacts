### Artifact: `FWMP_constraints.f95`

#### Description:
A Fortran 95 program to verify the following MILP assignment constraints in the conference article: (16), (24), (25), (26), and (27), with example data corresponding to that of Figures 2 & 3 and equations (28) & (29).

#### Requirements:
* a Fortran 95-compatible compiler, e.g. [gfortran](https://gcc.gnu.org/wiki/GFortran);
* at least version 3.10 of [CMake](https://cmake.org/).

#### Build and Run on *nix Systems:
* execute `ccmake .` where `FWMP_constraints.f95` is located on your system, or replace `.` with the path to it if an out-of-source build is preferred, and select the desired Fotran compiler;
* configure by pressing `c` then generate the `makefile` by pressing `g`;
* build with `make`;
* run the generated `assignments` executable.

#### What to Expect:
A text output in the terminal that will verify the aforementioned equations and examples.

