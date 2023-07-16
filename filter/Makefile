start_playbook:
	ansible-playbook -i inventory.ini playbook.yml

list_servers:
	ansible-inventory -i inventory.ini --list

graph_servers:
	ansible-inventory -i inventory.ini --graph

show_facts:
	ansible all -i inventory.ini -m setup | less

write_facts:
	ansible all -i inventory.ini -m setup | less >> list.txt

