# ansible-remote-vagrantfile
## Library of shared vagrantfiles

This git repo drives the shared vagrantfiles used for Ansible role testing.
And came from my work originally here:

https://github.com/bbc/rd-ansible-remote-vagrantfile

## Usage
This repo contains an 'example_shim', simply place this with the name 'Vagrantfile' in the repository. Then define the remote vagrantfile using the variable:

```remote_vagrantfile = "https://raw.githubusercontent.com/boxrick/ansible-remote-vagrantfile/master/vagrantfile_ansible_roles"```

it will pull in a remote Vagrantfile.

### Current vagrantfile:

+ vagrantfile_ansible_roles
> This is a shared generic vagrantfile which has docker and various distros including Centos6,7, Ubuntu 16 and 18. Designed for fairly generic role testing.
