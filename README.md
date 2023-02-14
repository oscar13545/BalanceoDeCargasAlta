# Balanceo de cargas de alta disponibilidad

Este es el archivo de Ansible para configurar los contenedores que tendrán las tres aplicaciones y junto con su balance de cargas

# ¿Cómo funciona?
Funciona de tal manera que lo que hace es que primero instala git y luego trae el repositorio, después instala Docker, y por último abre la carpeta del repositorio, y ejecuta el Dockerfile

Para utilizarlos se debe de correr el comando:
ansible-playbook playbook.yml -e 'ansible_python_interpreter=/usr/bin/python3'
