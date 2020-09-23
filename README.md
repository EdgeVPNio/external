# external repository

This repository contains the third-party libraries used in the EdgeVPNio/evio build

## Supported Operating Systems/Platforms

* Ubuntu 18 and 20 - x64
* Raspbian Stretch on Raspberry Pi 3 and 4 - ARM7
* Raspbian Stretch on Raspberry Pi Zero - ARM6
* Microsoft Windows 10 - x64

The third-party libraries for the above systems are located in their respective repository branches.

## Cloning a Single Branch
To clone a single branch, rather than the entire repository, use the following command:

```
git clone -b <branch_name> --single-branch <uri>
```

For instance:

```
git clone -b ubuntu-x64 --single-branch https://github.com/EdgeVPNio/external.git
```
