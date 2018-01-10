# ansible-basic
Basic set of ansible playbooks and roles

This can be used as a base when setting up a larger ansible environment.

## Example setup

Example files can be found in the example directory
```
$basedir/inventory
        /host_vars/*
        /group_vars/all.yaml
        /basic (clone of ansible-basic repo)
 
```

### Run playbook

```
ansible-playbook basic/common.yaml
```
