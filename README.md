# dev-env-playbooks
Ansible playbooks used to set up a dev environment.

To run locally, add the following to /etc/hosts/ansible.
```
localhost ansible_connection=local
```

Run one of the playbooks with ansible-playbook. 
```
ansible-playbook --extra-vars="release=focal" install_docker/playbook.yml
```
