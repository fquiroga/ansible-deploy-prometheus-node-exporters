Ansible Playbook for Node Exporter and Prometheus

This Ansible playbook installs and configures Node Exporter and Prometheus on your target machines.

Requirements

- Ansible 2.9 or higher
- Target machines running a Debian-based Linux distribution (e.g., Debian, Ubuntu)

Usage

1. Update your inventory file with the target machines you want to install Node Exporter and Prometheus on.
2. Configure the variables in vars/main.yml
3. Run the playbook:

    ansible-playbook -i inventory.yml playbook.yml

    