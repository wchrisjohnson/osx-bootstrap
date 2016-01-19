# Overview
This repository contains the Ansible playbooks necessary to install and configure the machines I manage. Ansible offers a multitude of ways to orchestrate an installation; this is my approach.

What I've done is heavily influenced by superlumic; I may end up just using his stuff fully. For now, I wanted to try to do it as simply as possible.

# Preparation
1. Install 1Password from the Apple Store; sync with iCloud.
2. Install work related SSH keys from 1Password.
	- copy files from 1Password to ~/.ssh
	- chmod 700 ~/.ssh/id_rsa
3. Clone this repo locally & cd into the repo folder

# Let's do this!
```
./bootstrap hpe-mbp.yml
```

# ToDo
* Figure out how to automate the handling of the prezto .rc files
```
setopt EXTENDED_GLOB
for rcfile in "${ZDOTDIR:-$HOME}"/.zprezto/runcoms/^README.md(.N); do
  ln -s "$rcfile" "${ZDOTDIR:-$HOME}/.${rcfile:t}"
done
````

# Apps that require manual install
* Microsoft OneNote (App Store)
* Microsoft Office 2011/2016
* Junos Pulse
