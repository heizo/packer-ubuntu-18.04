# packer-ubuntu-18.04
==============
### Overview

A packer template to create Ubuntu 18.04 "Bionic Beaver" Server boxes for vagrant.

### USAGE
To create VirtualBox virtual machine.
```sh
    packer build ubuntu.json
```
To create Hyper-V virtual machine.
```sh
    packer build ubuntu-hyperv.json
```

### Ubuntu 18.04.5
Tested with [packer][] 1.6.1, [Vagrant][] 2.2.9, [VirtualBox][] 6.1.12

[Packer]: https://packer.io/
[Vagrant]: https://www.vagrantup.com/
[VirtualBox]: https://www.virtualbox.org/
