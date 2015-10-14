# Overview
This repository contains the Ansible playbooks necessary to install and configure all of the machines I manage. There are numerous ways to use Ansible to orchestrate the installation of stuff; this is my approach.

My approach is influenced heavily by superlumic; I may end up just using his stuff fully. For now, I wanted to try to do it as simply as possible.

# Start from Square 1
1) Install 1Password from the Apple Store; sync with iCloud.
2) Install work related SSH keys from 1Password.
	- copy files from 1Password to ~/.ssh
	- chmod 700 ~/.ssh/id_rsa

# Let's do this!
```
./bootstrap
```