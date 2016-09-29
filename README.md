# Ansible Role: nrpe

Install and configure nrpe client

## Requirements

CentOS 6 Minimal Installation

## Example Playbook

`install-nrpe.yml`

    - hosts: all
      remote_user: root

      roles:
        - nrpe

Running playbook on specific hosts:

    ansible-playbook -i host1.example.com,host2.example.com install-nrpe.yml

## License

MIT
