# dev-env-playbooks
Ansible playbooks used to set up common development tools.

To run locally, add the following to /etc/hosts/ansible.
```
localhost ansible_connection=local
```

Run one of the playbooks with ansible-playbook. 
```
ansible-playbook --extra-vars="release=focal" install_docker/playbook.yml
```
Refer to the [Ansible Documentation](https://docs.ansible.com/) for further information on use of Ansible.
