# ansible-playbooks
My Ansible Playbooks

``` bash
# Debian 10
apt-get -t buster-backports install ansible
ansible-galaxy collection install community.general
ansible-galaxy collection install ansible.posix
```

```bash
ansible-playbook playbooks/docker.yml  -i hosts
```

# Postgres 12 development host on debian 11
```bash
ansible-playbook playbooks/postgres-develop.yml  -i hosts
```

