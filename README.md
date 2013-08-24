awx-cli
=======

This is a command line tool for AnsibleWorks AWX.  

About AWX
=========

AWX is a GUI and REST interface for Ansible that supercharges it by adding RBAC,
centralized logging, autoscaling/provisioning callbacks, graphical inventory
editing, and more.

See http://ansibleworks.com/ansibleworks-awx for more details.  AWX is free to use for up to 10 nodes, and you can purchase a license for more at http://store.ansibleworks.com.

Capabilities
============

You can use this command line tool to send commands to the AWX API.

For instance, you might use this tool with Jenkins, cron, or in-house software to trigger remote execution of Ansible playbook runs.

This tool is designed to be pluggable and will be expanded over time.

Installation
============

Packages will be coming soon.

From a git checkout:
  
    make install
    awx-cli --help

Usage
=====

    awx-cli --help

License
=======

While AWX is commercial software, awx-cli is an open source project and we want
to encourage contributions to it.  Specfically, this CLI project is licensed under the
Apache2 license.  You may do what you like with it, but we definitely welcome
pull requests!

Michael DeHaan
(C) 2013, AnsibleWorks, Inc.

