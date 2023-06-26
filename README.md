# ansible-aruba-sw-os-s
ansible aruba switch os-s

# requirement
ansible

pyhton

pip install --user ansible-pylibssh

pip install paramiko

# run
ansible-playbook backup-config.yaml -i list-switch.yaml --vault-password-file @your.vault.password.file