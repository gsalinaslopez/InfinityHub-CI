# InfinityHub-CI

The purpose of this Repository is to provide a way to build containers similar to what are provided on [AMD's Infinity Hub](https://www.amd.com/en/technologies/infinity-hub).  
Each builds provides parameters to specify different source code branches, release versions of [ROCm](https://github.com/RadeonOpenCompute/ROCm), [OpenMPI](https://github.com/open-mpi/ompi), [UCX](https://github.com/openucx/ucx), and different versions Ubuntu to be build in. 

## Single-Node Server Requirements
| CPUs | GPUs | Operating Systems | ROCm™ Driver | Container Runtimes | 
|---- |---- |----------------- |------------ |------------------ | 
| X86_64 CPU(s) | AMD Instinct MI200 GPU(s) <br>  AMD Instinct MI100 GPU(s) | Ubuntu 20.04 <br> Ubuntu 22.04 <BR> RHEL8 <br> RHEL9 <br> SLES 15 sp4 | ROCm v5.x compatibility |[Docker Engine](https://docs.docker.com/engine/install/) <br> [Singularity](https://sylabs.io/docs/) |

For ROCm installation procedures and validation checks, see:
* [ROCm Documentation](https://rocm.docs.amd.com)
* [AMD Lab Notes ROCm installation notes](https://github.com/amd/amd-lab-notes/tree/release/rocm-installation).
* [ROCm Examples](https://github.com/amd/rocm-examples)

## Applications:
- [AMD Base Docker Container for GPU-Aware MPI in ROCm applications](/base-gpu-mpi-rocm-docker/)
- [AMD's Implementation of Gromacs with HIP](/gromacs/)
  - [Bare Metal](/gromacs/baremetal/)
  - [Docker](/gromacs/docker/)
- [Cholla](/cholla)
  - [Bare Metal](/cholla/baremetal/)
  - [Docker](/cholla/docker/)
- [CP2K](/cp2k/)
  - [Bare Metal](/cp2k/baremetal/)
  - [Docker](/cp2k/docker/)
- [Grid](/grid/)
  - [Docker](/grid/docker/)
- [HPCG in Docker](/hpcg-docker/)
- [LAMMPS in Docker](/lammps-docker/)
- [OpenFOAM in Docker](/openfoam-docker/)
- [OpenMM in Docker](/openmm-docker/)
- [PETSc in Docker](/petsc-docker/)
- [PyFR in Docker](/pyfr-docker/)
- [rocHPL](/rochpl/)
  - [Docker](/rochpl/docker/)
  - [Spack](/rochpl/spack/)
- [Specfem3D- Cartesian](/specfem3d/)
