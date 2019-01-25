# EMEWS Spack Repository

This repository provides Spack-based installations for EMEWS software. These steps will add this repository to a Spack installation:

* If Spack is not installed yet, [install Spack](https://spack.readthedocs.io/en/latest/getting_started.html) and set up Spack shell support, e.g., for bash 
  * ``. [path to spack]/share/spack/setup-env.sh``
* Clone the EMEWS Spack repository
  * ``git clone https://github.com/emews/spack_emews``
* Change directory into the repository
  * ``cd spack_emews``
* Add the EMEWS Spack repository to your existing Spack repository or repositories
  * ``spack repo add .``