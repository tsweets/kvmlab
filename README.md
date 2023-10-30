### Purpose
Automate the provisioning VMs via libvirt and Ansible
based off of https://www.redhat.com/sysadmin/build-VM-fast-ansible
### Install Deps
 ansible-galaxy collection install community.libvirt
### Run
 ansible-playbook -K kvm_provision.yml