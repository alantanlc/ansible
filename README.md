# Ansible

IT Automation

## Commands

Test connection to servers:
```
ansible -i ./inventory/hosts servers -m ping --user <username> --private-key <private-key-file>
```

Execute playbook:
```
ansible-playbook ./playbooks/<yml_file> --user <username> --private-key <private-key-file> -i ./inventory/hosts
```
