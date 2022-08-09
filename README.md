# ansible-playbook

## roles:
- jira
- confluence

### Run
```bash
$ ansible-galaxy collection install community.general
$ ansible-galaxy install -r roles/requirements.yml
$ ansible-playbook -i inventories/dev/ -vvv --private-key ~/.ssh/vm_id_rsa.key.key playbook.yml
```