start_playbook:
	time ansible-playbook -i inventory.ini playbook.yml
# time - Measure the Ansible Playbook runtime

list_servers:
	ansible-inventory -i inventory.ini --list

graph_servers:
	ansible-inventory -i inventory.ini --graph

show_facts:
	ansible all -i inventory.ini -m setup | less

