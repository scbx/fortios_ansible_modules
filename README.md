# FortiOS FortiGate Ansible Modules
## Overview
I took some of the existing Ansible Modules from the Ansible Network Modules Repo for fortios and modified their code to do a few other things, functionality that doesn't seem to exist on the Ansible Network Module for FortiOS (that I am aware of). These modules provided configuration capability that was a requirement of mine to extend automated fortios provisioning through ansible / the fortios api.
The titles give an overview of what the module does, it's mostly using the monitor / execute methods within the fortiosapi as it doesn't seem to be much with that in the ansible network modules.

