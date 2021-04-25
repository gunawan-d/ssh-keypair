# ssh-keypair

1. Lakukan ping with ansible mengarah ke file Hosts

ansible webserver -i hosts -m ping

NB : sampai success

2.  Jalankan playbook Ansible
ansible-playbook -i hosts ssh-keypair.yml

