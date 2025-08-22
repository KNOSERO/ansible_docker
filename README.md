# Ansible Docker
Script for installing and configuring docker in Ansible

## Example

```yaml
- name: Install Docker
  hosts: all
  become: yes

  tasks:
    - name: Run install_docker.yml
      include_tasks: ./task/ansible_docker/playbook.yml
```

