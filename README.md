# Smooth Emulator software

Authors: Scott Pratt, Oleh Savchuk, Eren Erdogan, Ekaksh Kataria

To install, please first
* clone this repository,
* checkout the commit/tag associated with the desired version of smooth emulator, and
* change to the [software](/software) directory.

MacOS users can build the software package by executing
```
% INSTALL_MAC.sh
```
Linux users,
```
% INSTALL_LINUX_APT-GET.sh
```
The Mac script will install some standard packages (specific C++ compilers...) through the `homebrew` program; 
The Linux script, using `apt-get`.  Detailed installation directions and descriptions can be found in the [user manual](/doc/UserManual.pdf).  If you wish to use a different package manager, or if you wish to change which version of the various packages is installed, you can edit the script.

Release tarballs are located in the root of the repository, and the installation procedure from tarball is essentially the same as above.
