## [![DebOps](https://debops.org/images/debops-small.png)](https://debops.org) users

<!-- This file was generated by Ansigenome. Do not edit this file directly but
     instead have a look at the files in the ./meta/ directory. -->

[![Travis CI](https://img.shields.io/travis/debops/ansible-users.svg?style=flat)](https://travis-ci.org/debops/ansible-users)
[![test-suite](https://img.shields.io/badge/test--suite-ansible--users-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-users/)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-debops.users-660198.svg?style=flat)](https://galaxy.ansible.com/debops/users)


The `debops.users` Ansible role can be used to manage local user accounts and
groups. The role allows for certain operations inside of the home directories,
like configuration of the mail forwarding, SSH public keys or automatic
deployment of user configuration files (dotfiles).

### Installation

This role requires at least Ansible `v2.0.0`. To install it, run:

```Shell
ansible-galaxy install debops.users
```

### Documentation

More information about `debops.users` can be found in the
[official debops.users documentation](https://docs.debops.org/en/latest/ansible/roles/ansible-users/docs/).


### Role dependencies

- `debops.secret`

### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://debops.org/) for a complete solution to run your Debian-based infrastructure.





### Authors and license

- Maciej Delmanowski | [e-mail](mailto:drybjed@gmail.com) | [Twitter](https://twitter.com/drybjed) | [GitHub](https://github.com/drybjed)

License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of [DebOps](https://debops.org/). README generated by [ansigenome](https://github.com/nickjj/ansigenome/).
