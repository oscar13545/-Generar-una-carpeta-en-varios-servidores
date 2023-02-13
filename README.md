# Generar una carpeta en varios servidores
Genera una carpeta Alumno y crea el nombre del alumno como un archivo .txt
# Como funciona
La primera instruccion genera la carpeta y la segunda entra en la carpeta y agrega el archivo .txt


# El codigo para correr es:
ansible-playbook playbook.yml -e 'ansible_python_interpreter=/usr/bin/python3
