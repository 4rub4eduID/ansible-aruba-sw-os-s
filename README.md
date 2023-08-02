# ansible-aruba-sw-os-s
ansible aruba switch os-s

# requirement
ansible

pyhton

ansible-galaxy collection install arubanetworks.aos_switch

pip install --user ansible-pylibssh

pip install paramiko

# run using public key
ansible-playbook @your.ansible.yaml -i @your.inventory.yaml

# run using encyrypted password
ansible-playbook @your.ansible.yaml -i @your.inventory.yaml -vault-password-file @your.vault.password.file

# guide
https://github.com/aruba/aos-switch-ansible-collection