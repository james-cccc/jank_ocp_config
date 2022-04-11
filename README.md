Janky OpenShift 'Day2' Configuration
===================================================

This repository contains Ansible playbooks and roles to automate OpenShift configuration.

Be warned this is VERY dated and by no means complete so please think of this as either a basis for somthing else or as inspiration in doing OCP config with Ansible.

Some of the code here is very dubvious - I'm mainly just storing this for historical reasons. Please see my other repos for new better quality stuff.

Requirements
------------

The following Ansible collections are required:
- community.kubernetes

The following python packages are required:
- jmespath
- openshift
- kubernetes

The following packages are required:
- ansible

Role Variables
--------------

The role variables are all set in a single file inside the vars directory.
