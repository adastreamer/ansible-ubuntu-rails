# Ubuntu Rails Setup

## Software

```
ansible-playbook playbooks/software.yml
```

## Configs

### Run All Configs Setup

```
ansible-playbook playbooks/configs.yml
```

### Available Tasks

```
ansible-playbook playbooks/configs_nginx.yml
ansible-playbook playbooks/configs_postfix.yml
ansible-playbook playbooks/configs_opendkim.yml
ansible-playbook playbooks/configs_meram.yml
```
