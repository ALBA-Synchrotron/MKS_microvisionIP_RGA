# Project MKS_microvisionIP_RGA

Cpp project

This device server will control MKS Microvision IP RGA (Residual Gas Analyser).
The control is done though a Socket device.

## Cloning

```
git clone git@gitlab.esrf.fr:accelerators/Vacuum/MKS_microvisionIP_RGA
```

## Building and Installation

### Dependencies

The project has the following dependencies.

#### Project Dependencies 

* Tango Controls 9 or higher.
* omniORB release 4 or higher.
* libzmq - libzmq3-dev or libzmq5-dev.
* Socket TANGO class
  

#### Toolchain Dependencies 

* C++11 compliant compiler.
* CMake 3.0 or greater is required to perform the build. 
  


### Build

Instructions on building the project.

CMake example: 

```bash
cd project_name
mkdir build
cd build
cmake ../
make
```

Make example: 

```bash
cd project_name
make
```

