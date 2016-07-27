# README.md
# Ansible Role: Snapraid PPA

A Ansible role that installs Snapraid from its current PPA on Ubuntu.

## Requirements

* Ubuntu

## Role Variables

* none

## Dependencies

* python-apt


## Example Playbook

    - hosts: all
      roles:
        - { role: lonix.snapraid }

## License

MIT



[![Build Status](https://travis-ci.org/lonix/ansible-snapraid.svg?branch=master)](https://travis-ci.org/lonix/ansible-snapraid)
