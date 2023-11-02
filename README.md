# Semaphore Ansible Role

![Semaphore Logo](assets/semaphore.png)

![Lint badge](https://woodpecker.hyteck.de/api/badges/moan0s/ansible-role-semaphore/status.svg)

Semaphore is a responsive web UI for running Ansible playbooks. This role helps you to set up Semaphore:

- with everything run in [Docker](https://www.docker.com/) containers
- powered by [the official Semaphore container image](https://hub.docker.com/r/semaphoreui/semaphore)


## Installing

To configure and install Semaphore on your own server(s), you should use a playbook like [Mother of all self-hosting](https://github.com/mother-of-all-self-hosting/mash-playbook) or write your own.

# Configuring this role for your playbook

```
semaphore_enabled: true
semaphore_hostname: 'example.org'

semaphore_db_host:

semaphore_db_name:
semaphore_db_user:
semaphore_db_password:
```
