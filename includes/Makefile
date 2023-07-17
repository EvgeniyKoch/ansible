start_playbook:
	ansible-playbook -i inventory.ini main.yml

list_servers:
	ansible-inventory -i inventory.ini --list

graph_servers:
	ansible-inventory -i inventory.ini --graph

show_facts:
	ansible all -i inventory.ini -m setup | less

