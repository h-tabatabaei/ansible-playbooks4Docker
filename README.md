# ansible-playbooks to install docker on Ubuntu hosts

## Usage

### Define the host

Hosts can be defined inside `/etc/ansible/hosts`, e.g.,
```sh
[local]
localhost
```

Otherwise, you can use the `-i inventory ` option to take the local `hosts` file.

### Apply docker role
Run ansible-playbook with given yaml file name, by default, will apply the
stack on all host.

e.g.,

```sh
$ ansible-playbook docker.yml
```
