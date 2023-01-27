# C Project Template

This is a template repo for setting up C projects quickly. 

This template includes a Makefile for building and installing a binary file onto a Linux system.

> If making an ```include``` folder, it should be placed inside the ```src``` directory

## Makefile building

The Makefile contains 3 commands:

### Build

Creates and links ```*.o``` files to create the ```EXEC.out``` file.

``` bash
make
```

### Install

Builds and copies the ```EXEC.out``` into ```/usr/local/bin/EXEC```.

``` bash
sudo make install
```

### Clean

Removes all ```*.o``` and ```*.out``` files.

``` bash
sudo make clean
```
