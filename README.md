hadoop-automation
=================

Collection of scripts to help automate the installation of Hadoop.

Files in `bin` must be in the users PATH on all machines.

`mr2trace-start-all.sh` is the primary script to start all Hadoop services across the cluster.
NOTE: This script assumes that you are executing it from a machine that will be part of the new Hadoop cluster.

`.environment-hadoop` should be loaded by all nodes in cluster, on euc this can easily be done by putting it in `$HOME/nfs/`

`mr2trace-config.sh` defines variables used across scripts, make sure that the `$MR2_SOURCE` correctly points to your compiled copy of hadoop

Lastly, if using with the euc cluster check out this repo to: `$HOME/nfs/`.
