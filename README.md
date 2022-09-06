# pi-kubed
Ansible Playbook to provision multi-master kubernetes cluster on Raspberry Pis

## Quick Start:
1. Install Ansible or setup an Ansible node (see the section: Setup an Ansible Node on Ubuntu)
2. Define your nodes in "hosts" file. They can be hostnames or IPs
3. Make sure you have passwordless sudo on the nodes, and passwordless SSH to the nodes from the host where you run ansible
4. Adjust settings in "roles/k8s/common/vars/main.yml"
5. Run the following command:
```
ansible-playbook -v mooh.yml
```
6. Profit
