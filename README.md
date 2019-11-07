# fiji-blur2d-ansible

the Fiji Java plugin here https://github.com/tischi/fiji-galaxy-blur2d 
creates the yaml file under roles/fiji-plugins/vars/main.yml

once the above file is created, run

ansible-playbook -i inventory galaxy.yml

the playbook will creates the tool xml wrapper, deploy it to the correct galaxy installation path, modify galaxy configs

