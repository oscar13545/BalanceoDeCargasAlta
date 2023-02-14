# Balanceo de cargas de alta disponibilidad

Este es el archivo de Ansible para configurar los contenedores que tendran las tres aplicaciones y junto con su balance de cargas

# ¿Cómo funciona?
Funciona de tal manera que lo que hace es que primero instala git y luego trae el repositorio, despues instala docker, y por ultimo abre la carpeta del repositorio e ejecuta el Dockfile

Para utilizarlos e debe de correr el comando: ansible-playbook playbook.yml -e 'ansible_python_interpreter=/usr/bin/python3'
