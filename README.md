## coreos-init

# Purpose

The intention of this project is for me to interactively learn more about the CoreOS installation and bootup process, ultimately as a stepping-stone in the direction of learning to fully use Kubernetes.

The project aims to answer the following questions:

1. What is the optimal method to deploy an entire Docker-based service architecture using CoreOS?
2. Is it possible to do this without using scripted logic?
3. Is it possible to design this system so it could be used by a developer sitting in a coffee shop with mininal server ops knowledge?
4. What is the best way to manage configuration components?
5. What is the best way to deliver these configuration component elements?
6. How can this be optimally structured so that code written on a laptop in a coffee shop can then be introduced to a production service stack with minimal or zero integration artifacting?

Note that this project aims to address automated deployment of a CoreOS VM, and does not seek to address questions about the containers running on said VM.
 
Useful links:

Instructions to install CoreOS to disk (note the special image used for VMWare):
https://coreos.com/os/docs/latest/installing-to-disk.html

Ignition configuration examples:
https://coreos.com/os/docs/latest/clc-examples.html

Provisioning:
https://coreos.com/os/docs/latest/provisioning.html
