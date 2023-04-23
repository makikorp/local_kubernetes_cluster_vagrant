# local_kubernetes-cluster_vagrant
HyperV_Vagrantfile

Vagrant is used to create a kubernetes cluster with Hyper-V

I use Vagrant to spin up a master and 2 worker nodes using an ubuntu image.
It also creates an NFS server to as a file system for the cluster

It calls bash shell scripts to provision the master and worker nodes, and nfs server.  It also gets the ip addresses to export nfs.   
