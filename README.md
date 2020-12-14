# tobias_richter.rrdtool

[![Build Status](https://github.com/tobias-richter/ansible-rrdtool/workflows/CI/badge.svg)](https://github.com/tobias-richter/ansible-rrdtool/actions)

This role compiles/setups rrdtool on Debian/Ubuntu systems

## Requirements

This role requires Ansible 2.7 or higher.

## Role Variables

See [defaults/main.yml](defaults/main.yml) for the documented role variables.

## Example Playbook

This playbook compiles/setups rrdtool in version 1.7.2.

    - hosts: rrdtool
	  roles:
	    - role: tobias_richter.rrdtool
	      rrdtool_version: 1.7.2