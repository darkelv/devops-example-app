deploy:
	ansible-playbook release.yml -i inventory.yml -u root --extra-vars="version=${V}" -vv

setup:
	ansible-playbook setup.yml -i inventory.yml -u root --extra-vars="version=${V}" -vv
