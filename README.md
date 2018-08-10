This document describes the steps to be able to run `ansible-playbook kubernetes-install.yaml` successfully.

1. This _playbook_ is created for Vagrant machines, so the user to log into the remote machines is `vagrant`.
1. The `ansible` SSH key has previously been copied on every machine of the cluster.
1. The IPs of the remote VMs match the ones on the `inventories/dev/hosts` file.

 
