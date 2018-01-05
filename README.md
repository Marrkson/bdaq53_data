This repository provides large binary data files for the bdaq53 readout system:
https://gitlab.cern.ch/silab/bdaq53

The git large file storage feature is used (git-lfs), to be able to store and track
larger data files. They are not part of the std. repository at cern.ch to avoid
blowing up the repository leading to slow I/O for push and pulls.

To use this repository the large file storage extension of git has to be installed.

Installation of git-lfs includes the git-lfs software package and the installation
of the extension to git. Git-lfs is a rather new feature and installation requires
a git version >= 1.8.2. New git version are usually not yet shipped within the
std. repositories thus git usually has to be upgraded first.

A usefull guide for all operating systems can be found here:
https://github.com/git-lfs/git-lfs/wiki/Installation
