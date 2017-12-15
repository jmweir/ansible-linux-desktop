# Linux Desktop Ansible Playbook

This is a playbook for setting up a Linux desktop environment.

## Local Testing
### Start Container

    $ docker-compose up -d

### Deploy

    $ ansible-playbook -i environments/docker site.yml

### RDP Login

    User: desktop
    Password: monkey
    
## Cleanup
### Stop Docker Containers

    $ docker-compose down
