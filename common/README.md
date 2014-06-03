# Common Playbook

This is the most basic of all playbooks to setup/bootstrap an Ansible
managed system.  This playbook provides:

* Git
* Python (including virtualenv and supervisor)

All variables will be listed in `defaults` and that folder will be symlinked
to the `defaults` folder in each of the various different OS flavors.

* MacOSX [`osx`]
* Ubuntu [`ubuntu`]

OS independent tasks will be located in their respective subdirectories.
