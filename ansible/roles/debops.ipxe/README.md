## [![DebOps project](http://debops.org/images/debops-small.png)](http://debops.org) ipxe

[![Travis CI](http://img.shields.io/travis/debops/ansible-ipxe.svg?style=flat)](http://travis-ci.org/debops/ansible-ipxe) [![test-suite](http://img.shields.io/badge/test--suite-ansible--ipxe-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-ipxe/)  [![Ansible Galaxy](http://img.shields.io/badge/galaxy-debops.ipxe-660198.svg?style=flat)](https://galaxy.ansible.com/list#/roles/3444)

[iPXE](http://ipxe.org/) is a network boot loader which allows you to boot
host operating systems in different ways, including over HTTP, from local
NFS or ISCSI server, etc.

This Ansible role configures iPXE configuration files on a specified host
which can be served to the other hosts on the network using TFTP or HTTP
server. You can use
[debops.dnsmasq](https://github.com/debops/ansible-dnsmasq) or
[debops.dhcpd](https://github.com/debops/ansible-dhcpd/) +
[debops.tftpd](https://github.com/debops/ansible-tftpd/) Ansible roles to
serve these configuration files to your hosts.

### Installation

This role requires at least Ansible `v1.7.0`. To install it, run:

    ansible-galaxy install debops.ipxe

### Documentation

More information about `debops.ipxe` can be found in the
[official debops.ipxe documentation](http://docs.debops.org/en/latest/ansible/roles/ansible-ipxe/docs/).


### Role dependencies

- `debops.apt_preferences`

### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://github.com/debops/debops) for a complete solution to run your Debian-based infrastructure.





### Authors and license

`ipxe` role was written by:
- Maciej Delmanowski | [e-mail](mailto:drybjed@gmail.com) | [Twitter](https://twitter.com/drybjed) | [GitHub](https://github.com/drybjed)

License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of the [DebOps](http://debops.org/) project. README generated by [ansigenome](https://github.com/nickjj/ansigenome/).