# Ansible Documentation

Ansible provides open-source automation that reduces complexity and runs everywhere. Using Ansible lets you automate virtually any task. Here are some common use cases for Ansible:
Eliminate repetition and simplify workflows

Manage and maintain system configuration

Continuously deploy complex software

Perform zero-downtime rolling update

# As automation technology, Ansible is designed around the following principles:
Agent-less Architecture,

Simplicity,

Scalability and flexibility,

Idempotence and predictability.

# Start automating with Ansible
1. install
    pip install ansible

2. Create a project folder on your filesystem
    mkdir ansible_quickstart && cd ansible_quickstart
    # Building an inventory
Continue getting started with Ansible and build an inventory as follows:
1. Create a file named inventory.ini in the ansible_quickstart directory that you created in the preceding step.

2. Add a new [myhosts] group to the inventory.ini file and specify the IP address or fully qualified domain name (FQDN) of each host system.