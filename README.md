# tobias_richter.rrdtool

[![Build Status](https://travis-ci.org/tobias-richter/ansible-rrdtool.svg?branch=master)](https://travis-ci.org/tobias-richter/ansible-rrdtool)

This roles compiles/setups rrdtool on Debian/Ubuntu systems

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