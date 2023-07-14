start_playbook:
	ansible-playbook playbook.yml -i inventory.ini

check_apt_update:
	ansible-playbook --check playbook.yml -i inventory.ini -t apt_update

check_node:
	ansible-playbook --check playbook.yml -i inventory.ini -t node

check_git:
	ansible-playbook --check playbook.yml -i inventory.ini -t git

check_make:
	ansible-playbook --check playbook.yml -i inventory.ini -t make

skip_make:
	ansible-playbook --check playbook.yml -i inventory.ini --skip-tags make

check_aria:
	ansible-playbook --check playbook.yml -i inventory.ini -t arya

check_tiron:
	ansible-playbook --check playbook.yml -i inventory.ini -t tiron

skip_users:
	ansible-playbook --check playbook.yml -i inventory.ini --skip-tags users
