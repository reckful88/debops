## [![DebOps project](http://debops.org/images/debops-small.png)](http://debops.org) bootstrap

[![Travis CI](http://img.shields.io/travis/debops/ansible-bootstrap.svg?style=flat)](http://travis-ci.org/debops/ansible-bootstrap) [![test-suite](http://img.shields.io/badge/test--suite-ansible--bootstrap-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-bootstrap/)  [![Ansible Galaxy](http://img.shields.io/badge/galaxy-debops.bootstrap-660198.svg?style=flat)](https://galaxy.ansible.com/list#/roles/4375)

`debops.bootstrap` is an Ansible role that helps you prepare a given
Debian/Ubuntu host to be managed by Ansible. It will install required
Python packages, configure hostname and domain, create an admin account and
set up SSH public keys for passwordless SSH access.

### Installation

This role requires at least Ansible `v1.8.0`. To install it, run:

    ansible-galaxy install debops.bootstrap

### Documentation

More information about `debops.bootstrap` can be found in the
[official debops.bootstrap documentation](http://docs.debops.org/en/latest/ansible/roles/ansible-bootstrap/docs/).



### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://github.com/debops/debops) for a complete solution to run your Debian-based infrastructure.





### Authors and license

`bootstrap` role was written by:
- Maciej Delmanowski | [e-mail](mailto:drybjed@gmail.com) | [Twitter](https://twitter.com/drybjed) | [GitHub](https://github.com/drybjed)

License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of the [DebOps](http://debops.org/) project. README generated by [ansigenome](https://github.com/nickjj/ansigenome/).
