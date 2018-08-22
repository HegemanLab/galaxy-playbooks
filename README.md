# Galaxy Playbook

[HegemanLab/galaxy-playbooks](#) contains several Galaxy Playbooks for deploying and managing Galaxy servers. These playbooks are dependent on several Ansible Roles forked from the Galaxy Project.

**These playbooks and roles are experimental and not ready for production.**

## Goals

- Provide general and metabolomics centric Galaxy Playbooks for deployment and management.
- Release Playbook versions as Galaxy versions are released.
- Use forked GalaxyProject Ansible Roles which can be rebased and with feature branches which can be cleanly pulled back.

## Playbooks

This repo will contain several playbooks for deploying Galaxy servers in the Hegeman Lab.

| Playbook             | Applicantion                            |
|----------------------|-----------------------------------------|
| galaxy-dev.yml       | Installs a standalone Galaxy server which uses the default UWSGI webserver and, single-user, SQLite database. |
| galaxy-stack.yml     | Installs Galaxy, NGINX, and Postgresql. |

## Roles 

Currently, roles must be linked, or downloaded, to the `roles/` folder for playbooks to work. Rename every role to remove the prepended `ansible-`.

Roles:
- [ansible-galaxy](https://github.com/HegemanLab/ansible-galaxy) a [GalaxyProject fork](https://github.com/GalaxyProject/ansible-galaxy)
- [ansible-galaxy-os](https://github.com/HegemanLab/ansible-galaxy-os)
- [ansible-nginx](https://github.com/HegemanLab/ansible-nginx) a [GalaxyProject fork](https://github.com/HegemanLab/ansible-nginx)
- [ansible-postgresql](https://github.com/HegemanLab/ansible-postgresql) a [GalaxyProject fork](https://github.com/HegemanLab/ansible-postgresql)
- [ansible-postgresql-objects](https://github.com/HegemanLab/ansible-postgresql-objects) a [natefoo fork](https://github.com/natefoo/ansible-postgresql-objects)
