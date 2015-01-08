Looking Glass
============

[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/getglass/looking-glass?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Looking Glass is a set of technologies to create, manage and maintain a company's networks and services. 

Core technologies
-----------------
* Ansible
* LizardFS

Goals
-----
* (Almost) zero touch service deployment
* Builds highly available services
* Builds horizontally scalable services

Getting Started
===============

Usage
-----
First-time usage:
* Install Ansible and sshpass on your management workstation
* Clone the Looking Glass repositories.

`git clone https://github.com/getglass/looking-glass.git`

`git clone https://github.com/getglass/looking-glass-secrets.git`

* Follow the instructions for the looking-glass-secrets repository
* Run 'sudo adduser glass' and 'sudo adduser glass sudo' on machines you want to manage.
* Run 'ansible-playbook site.yml -i inventory --ask-pass --ask-sudo-pass'

Contact Us
==========

IRC
---
You can find us on IRC at #lookingglass on irc.freenode.net. The IRC channel is a good place to get help or discuss development of Looking Glass.

Project Details
===============

License
-------
looking-glass and looking-glass-secrets are made available under the MIT license. See the [LICENSE](LICENSE) file for details.

Branch Info
-----------
* Releases are named after Cloud Cult songs.
* The 'master' branch corresponds to the release actively under development.
* Various release-X.Y branches exist for previous releases.
