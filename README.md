# Summer School Tools for Weeks 1 and 2

## System requirements:

   * The system must have libedit installed. For the yum package manager, the
     package is called libedit-devel; for apt-get, it is libeditline-dev. Some
     systems have *both* packages. In that case please use libedit, not libeditline.
   * The system should have zlib installed
   * The system should have the macro pre-processing package m4 installed

## To install tools:
 
  * Clone this repository with `git clone https://github.com/asyncvlsi/summer2022`. 
  * Note that this repository contains submodules, so make sure you initialize those as well (`git submodule update --init --recursive`)
   * Create a directory where you'd like the tools to be installed. Example
     common locations on Unix-like machines include /usr/local/cad, /opt/cad, /opt/async. You can also install them in any other directory (e.g. $HOME/async)
   * Set the environment variable ACT_HOME to point to the install directory.
   * Run ./build
