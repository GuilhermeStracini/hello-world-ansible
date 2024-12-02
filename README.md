# Hello World Ansible

📚 A repository to explore and learn **[Ansible](https://www.ansible.com/)**, a powerful open-source automation tool for configuration management, application deployment, and task orchestration.

---

## Overview

This repository provides hands-on examples to get started with Ansible, focusing on:

- Writing and testing **playbooks** for automation tasks.
- Understanding and creating **inventories** for target systems.
- Exploring integrations with tools like Docker, Terraform, and CI/CD pipelines.

Ansible enables infrastructure automation with a simple and agentless architecture, making it ideal for system administrators and DevOps engineers.

---

## Features

- **Beginner-Friendly**:
  - Step-by-step examples for setting up and running Ansible.
  - Basic playbooks for common automation tasks.

- **Advanced Use Cases**:
  - Demonstrates integration with tools like **Docker** and **Terraform**.
  - Includes examples for CI/CD pipelines and infrastructure orchestration.

- **Testing with Docker**:
  - Learn how to test Ansible playbooks locally using Docker containers.

---

## Getting Started

Follow these steps to set up and use Ansible locally.

### Prerequisites

- Install **Ansible**: Follow the [official installation guide](https://docs.ansible.com/ansible/latest/installation_guide/index.html).
- Optionally, install **Docker** if testing playbooks in a containerized environment: [Docker Installation Guide](https://docs.docker.com/get-docker/).

### Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/GuilhermeStracini/hello-world-ansible.git
   cd hello-world-ansible
   ```

2. **Set Up an Inventory**:
   - Create or edit an inventory file to define your target systems.
   - Learn more: [Getting Started with Inventories](https://docs.ansible.com/ansible/latest/getting_started/get_started_inventory.html).

3. **Run a Playbook**:
   ```bash
   ansible-playbook -i inventory playbook.yml
   ```

4. **Test with Docker** (Optional):
   - Use Docker containers as target systems for testing:
     ```bash
     ansible-playbook -i docker_inventory.yml playbook.yml
     ```

---

## Helpful Links

Expand your knowledge with these resources:

- [Test Ansible Playbooks Using Docker](https://dev.to/pencillr/test-ansible-playbooks-using-docker-ci0)
- [Getting Started with Inventories](https://docs.ansible.com/ansible/latest/getting_started/get_started_inventory.html)
- [How to Build an Inventory the Right Way](https://lovethepenguin.com/ansible-how-to-build-an-inventory-the-right-way-ad62309e96cf)
- [Docker Containers with Ansible](https://medium.com/@Oskarr3/docker-containers-with-ansible-89e98dacd1e2)
- [RabbitMQ Cluster Setup with Terraform and Ansible](https://medium.com/@ratulbasak93/rabbitmq-cluster-setup-using-terraform-and-ansible-in-aws-fbd72f386b66)
- [Integrating Ansible with CI/CD Pipelines](https://medium.com/@vinoji2005/day-26-integrating-ansible-with-ci-cd-pipelines-284637f83ba2)
- [Ansible Installation and Configuration Guide](https://medium.com/cloud-native-daily/ansible-installation-and-configuration-guide-checks-disk-space-on-remote-servers-and-deletes-4b3292d4f52b)
- [Ansible vs. Terraform: Choose One or Use Both](https://medium.com/env0/ansible-vs-terraform-choose-one-or-use-both-1efd1d6c7fb1)
- [Using Docker Containers for Ansible Testing](https://www.dbi-services.com/blog/using-docker-containers-for-ansible-testing/)

---

## Contribution

Contributions are welcome! If you'd like to enhance this repository, feel free to:
- Fork the repository.
- Create a new branch for your feature or bug fix.
- Submit a pull request with a detailed description.

---

## License

This project is licensed under the [MIT License](LICENSE).
