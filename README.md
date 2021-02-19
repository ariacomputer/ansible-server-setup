# ansible-server-setup
Ansible server setup0

## Setup

### Requirements

- Requires Ansible v2.6+;
- Supports Ubuntu 20.10 Server.

### Installation

If configuring the [Datadog role](https://github.com/DataDog/ansible-datadog), it must be installed first:

```shell
ansible-galaxy install datadog.datadog 
```

To run, originally specifying a sudo password: 

    git clone https://github.com/ariacomputer/ansible-server-setup
    ansible-playbook site.yml -i hosts -u aria -kK

Afterward:

    ansible-playbook site.yml -i hosts -u ariacomputer