Ansible role to install docker on Centos7

# Setup the VM

```
vagrant up
```

# Launch ansible

```
ansible-playbook -i inventories/test playbook.yml
```

# Check

```
clear; vagrant ssh p10 -c "docker container ls"; vagrant ssh p11 -c "docker container ls"; vagrant ssh p12 -c "docker container ls"
```