# Demo VM
A virtual machine to demonstrate how all sitQA projects are integrated.

Runs all of these projects (and their dependencies) on a single VM:
- https://github.com/sitQA/exampleClient
- https://github.com/sitQA/context-manager
- https://github.com/sitQA/situation-quality-assessment
- https://github.com/fleetSim/trucksimulation
- https://github.com/fleetSim/trucksimulation-ui

## Setup
- Install vagrant and ansible
- run `vagrant up` in this folder -> vagarnt provisions the VirtualBox VM
- you can ssh into the vm with `vagrant ssh`
- forwarded ports should be displayed in the console by vagrant
