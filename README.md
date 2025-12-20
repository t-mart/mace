# simsbrook-router

An Ansible playbook to configure a Arch Linux router at our home on Simsbrook.

## Usage

Syntax check:

```bash
ansible-playbook -i inventory.yml playbook.yml --syntax-check
```

Check and diff:

```bash
ansible-playbook -i inventory.yml playbook.yml --check --diff
```

Run the playbook:

```bash
ansible-playbook playbook.yml
```
