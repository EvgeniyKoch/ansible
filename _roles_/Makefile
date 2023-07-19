start_servers: install_roles start_playbook

start_playbook:
	ansible-playbook -i inventory.ini playbook.yml

list_servers:
	ansible-inventory -i inventory.ini --list

graph_servers:
	ansible-inventory -i inventory.ini --graph

show_facts:
	ansible all -i inventory.ini -m setup | less

install_roles:
	ansible-galaxy install -r requirements.yml
