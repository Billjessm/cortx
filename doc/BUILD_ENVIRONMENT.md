### BUILD AND TEST ENVIRONMENT FOR CORTX

Building and testing CORTX can be done using a single system.  Obviously CORTX is designed to be a scale-out distributed object storage system but these instructions currently only cover setting up a single node environment.

Currently CORTX requires the CentOS 7.7.1908 distribution running the 3.10.0-1062 kernel. Building it and testing it can be done on either a physical or virtual machine matching these requirements.  

Please refer to [this page](LocalVMSetup.md) for information about running with VMWare Fusion or Virtual Box as well as links to downloadable VM images which you can use.  

__Seagate employees:__ *You cannot use Virtualbox or VMware Fusion on your Seagate machines. You may be able to request a virtual machine in our Seagate cloud. Please click [here](DEV_VM.md) for instructions about how to request one.* 

TODO:
1. Provide a downloadable image for Windows Subsystem Linux and any necessary instructions.

Planning to create your own VM? please check [this page](VIRTUAL_MACHINE.md) for helpful pre-build steps pertaining to motr, s3server and hare. It also contains information to resolve a few issues that can come up at runtime.
