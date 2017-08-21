execute on ansible localhost
ansible-playbook local.yml --connection=local --extra-vars "dns_master_ip=192.168.15.3"
