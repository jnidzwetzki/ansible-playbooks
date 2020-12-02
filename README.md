# ansible-playbooks
My Ansible Playbooks

``` bash
# Debian 10
apt-get -t buster-backports install ansible
ansible-galaxy collection install ansible.posix
```

```bash
ansible-playbook docker.yml -i hosts
```
