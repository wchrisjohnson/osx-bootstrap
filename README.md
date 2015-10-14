# Overview
This repository contains the Ansible playbooks necessary to install and configure the machines I manage. There are numerous ways to use Ansible to orchestrate the installation of stuff; this is one approach.

My approach is influenced heavily by superlumic; I may end up just using his stuff fully. For now, I wanted to try to do it as simply as possible.

# Prepare the mac
1. Install 1Password from the Apple Store; sync with iCloud.
2. Install work related SSH keys from 1Password.
	- copy files from 1Password to ~/.ssh
	- chmod 700 ~/.ssh/id_rsa
3. Clone this repo locally & cd into the repo folder

# Let's do this!
```
./bootstrap
```