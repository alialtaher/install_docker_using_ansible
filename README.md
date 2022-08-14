# install_docker_using_ansible
install and configure Docker using Ansible


#put the IP/hostname of the client VM inside inventory file


#To run the installation playbook:
ansible-playbook -i inventory --ask-become-pass install-docker.yml


#To run the uninstallation playbook:
ansible-playbook -i inventory --ask-become-pass remove-docker.yml
