# home-lab
Scripts used to manage my home lab.


 Usage: ansible-playbook -i inventory --extra-vars "template_type=type vm_hostname=hostname vm_newid=id" proxmox.yaml
 Requirements: To use the proxmox modules, the following must be installed:
  - proxmoxer - pip install proxmoxer (python3 -m ensurepip --upgrade to install pip)
  - community.general
