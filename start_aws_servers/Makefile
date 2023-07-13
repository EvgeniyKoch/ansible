uptime_appservers:
	ansible appservers -i inventory.ini -a 'uptime'

uptime_webservers:
	ansible webservers -i inventory.ini -a 'uptime'

uptime_allservers:
	ansible all -i inventory.ini -a 'uptime'

ping_appservers:
	ansible -i inventory.ini -m ping appservers

ping_webservers:
	ansible -i inventory.ini -m ping webservers

ping_allservers:
	ansible -i inventory.ini -m ping all
