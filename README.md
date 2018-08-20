# Galaxy Playground

**These playbooks and roles are mostly experimental forks from the GalaxyProject.**

Ansible playbooks for deploying and managing Galaxy servers.

This repo will contain several playbooks for deploying Galaxy servers in the Hegeman Lab.

| Playbook         | Applicantion                           |
|------------------|----------------------------------------|
| galaxy.yml       | Installs a standalone Galaxy server    |
| galaxy-stack.yml | Installs Galaxy, NGINX, and Postgresql |

Currently, roles must be linked or downloaded to the `roles/` folder for playbooks to work. Rename every role to remove the prepended `ansible-`.

Roles:
[https://github.com/HegemanLab/ansible-galaxy](https://github.com/HegemanLab/ansible-galaxy)
[https://github.com/HegemanLab/ansible-galaxy-os](https://github.com/HegemanLab/ansible-galaxy-os)
[https://github.com/HegemanLab/ansible-nginx](https://github.com/HegemanLab/ansible-nginx)
[https://github.com/HegemanLab/ansible-postgresql](https://github.com/HegemanLab/ansible-postgresql)
[https://github.com/HegemanLab/ansible-postgresql-objects](https://github.com/HegemanLab/ansible-postgresql-objects)

