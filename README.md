# Overview
This repository contains the Ansible playbooks necessary to install and configure all of the machines I manage. There are numerous ways to use Ansible to orchestrate the installation of stuff; this is my approach.

# The nitty gritty







This is how I organise my config files:
* base - The "base" role includes all of the common stuff I install across machines.
* work - The "work" role include stuff specific to work
* <machine>.yml - This is the highest level playbok for a specific machine, and is used to bring in all of the stuff I want on that specific machine.

# Let's do this!
