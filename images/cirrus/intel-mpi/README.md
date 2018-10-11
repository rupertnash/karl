# Intel MPI

You need to get the Intel MPI for Linux library tarball from their website (and agree to the licence).

Currently the URL is https://software.intel.com/en-us/mpi-library/choose-download/linux

The version probably has to match the version installed on your cluster. For Cirrus in October 2018, this is 2017.2.174

Then you can build the base image using the Packer template `common.json`, optionally overriding the default variables

```
packer build common.json
```

