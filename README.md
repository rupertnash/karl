# Karl
## Helper tools for creating Singularity Images

## Build environment

To enable building on non-Linux machines or machines where you don't
have root, there is a Vagrant setup in buildenv/ubuntu-18.04 (see
https://www.vagrantup.com/docs for help) which can be activated by:

```
cd buildenv/ubuntu-18.04
vagrant up
vagrant ssh
```

This will give you a terminal inside a VM with Docker, Singularity,
Packer and Ansible installed.

You can stop the VM with `vagrant suspend`, `vagrant halt`, or
`vagrant destroy` (see
https://www.vagrantup.com/intro/getting-started/teardown.html for the
difference.

There is a partial equivalent of this on Centos 7 om buildenv/centos-7
