# Ansible Docker Apache Deployment

This repository contains an Ansible playbook to deploy an Apache server inside a Docker container. The container runs on a custom network subnet `172.168.10.0/30`.

## Usage

1. Clone the repository.
2. Edit `docker_deploy.yml` if necessary.
3. Run the playbook with `ansible-playbook docker_deploy.yml`.

## Prerequisites

- Docker installed on the target machine(s).
- Ansible installed on the control machine.