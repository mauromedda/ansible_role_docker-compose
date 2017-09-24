# Ansible Role: docker-compose

An Ansible Role that installs docker-compose on RHEL/CentOS.

## Requirements

None.

## Role Variables

None.

## Dependencies

  - mauromedda.ansible_role_epel
  - mauromedda.ansible_role_pip
  - mauromedda.ansible_role_docker-py

## Example Playbook

```
    - hosts: servers
      roles:
        - { role: mauromedda.ansible_role_epel }
        - { role: mauromedda.ansible_role_pip }
        - { role: mauromedda.ansible_role_docker-py }
        - { role: mauromedda.ansible_role_docker-compose }
```

## License

BSD

## Author Information

Mauro Medda
