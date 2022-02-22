![lint workflow](https://github.com/noaa-ocs-modeling/OCSMesh/actions/workflows/pylint.yml/badge.svg?branch=main)
![fnc workflow](https://github.com/noaa-ocs-modeling/OCSMesh/actions/workflows/functional_test.yml/badge.svg?branch=main)

## OCSMesh
### A Python package for processing DEM data into georeferenced unstructured meshes using the [jigsaw-python](https://github.com/dengwirda/jigsaw-python) library.

#### Installation
The Jigsaw library must be initialized first by running `./setup.py install_jigsaw`, then, the package can be installed normally by doing `./setup.py install`:

```bash
./setup.py install_jigsaw # installs the Jigsaw C-library to the current Python environment
./setup.py install # Installs the OCSMesh library to the current Python environment
./setup.py develop # run this if you are a developer.
```
#### Requirements
* 3.7 <= Python < 3.10
* CMake 
* C/C++ compilers

## How to Cite
Title : OCSMesh: a data-driven automated unstructured mesh generation software for coastal ocean modeling

Personal Author(s) : Mani, Soroosh;Calzada, Jaime R.;Moghimi, Saeed;Zhang, Y. Joseph;Myers, Edward;Pe’eri, Shachak;

Corporate Authors(s) : Coast Survey Development Laboratory (U.S.)

Published Date : 2021

Series : NOAA Technical Memorandum NOS CS ; 47

DOI : https://doi.org/10.25923/csba-m072

