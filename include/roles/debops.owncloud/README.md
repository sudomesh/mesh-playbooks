## [![DebOps project](http://debops.org/images/debops-small.png)](http://debops.org) owncloud

[![Travis CI](http://img.shields.io/travis/debops/ansible-owncloud.svg?style=flat)](http://travis-ci.org/debops/ansible-owncloud) [![test-suite](http://img.shields.io/badge/test--suite-ansible--owncloud-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-owncloud/)  [![Ansible Galaxy](http://img.shields.io/badge/galaxy-debops.owncloud-660198.svg?style=flat)](https://galaxy.ansible.com/list#/roles/1584)


***

This role installs [ownCloud](http://owncloud.org/) instance on a
specified host, with either sqlite, MySQL or PostgreSQL database
as a backend and an nginx webserver as a frontend.

Currently only ownCloud 8.0 is supported because for older
versions there are no complete deb-packages available.

### Installation

This role requires at least Ansible `v1.7.0`. To install it, run:

    ansible-galaxy install debops.owncloud

### Documentation

More information about `debops.owncloud` can be found in the
[official debops.owncloud documentation](http://docs.debops.org/en/latest/ansible/roles/debops.owncloud.html).


### Role dependencies

- `debops.secret`
- `debops.nginx`
- `debops.postgresql`
- `debops.php5`
- `debops.mysql`

### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://github.com/debops/debops) for a complete solution to run your Debian-based infrastructure.





### Authors and license

`owncloud` role was written by:
- Maciej Delmanowski | [e-mail](mailto:drybjed@gmail.com) | [Twitter](https://twitter.com/drybjed) | [GitHub](https://github.com/drybjed)
- Hartmut Goebel | [e-mail](mailto:'h.goebel@crazy-compilers.com) | [website](http://www.crazy-compilers.com) | [GitHub](https://github.com/htgoebel)

License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of the [DebOps](http://debops.org/) project. README generated by [ansigenome](https://github.com/nickjj/ansigenome/).
