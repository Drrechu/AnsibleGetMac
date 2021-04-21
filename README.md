#Ansible playbook to get information about device with given MAC address

# Usage
Run
```bash
ansible-playbook playbook.yml --extra-vars "mac_address=<your_mac_address> api_key=<your_api_key>"
```