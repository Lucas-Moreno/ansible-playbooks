# ansible-playbooks

RUN : ansible-playbooks nom_du_playbook

Ne pas oublier de mettre les variables d'environnements du bon playbook dans le fichier vars


# ssh_authorized_keys_vm

RUN : ansible-playbook -i inventory/inventory.ini ssh_authorized_keys_vm.yml

chmod 400 key

Remplacer les variables d'environnements de vars_ssh_authorized_keys_vm.yml et de inventory.ini