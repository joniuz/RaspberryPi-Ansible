# RaspberryPi-Ansible
Coleccion de scripts Ansible que permiten la instalacion de una Raspberry Pi - IoT Server desde cero

## Instalacion
Para instalar los pasos son
1. Realizar un update (siempre es recomendable)

sudo apt-get update

2. Instalar Ansible

sudo apt-get install ansible

3. Instalar git

sudo apt-get install git

4. Clonar el repositorio

git clone https://github.com/internetdelascosas/RaspberryPi-Ansible.git

## Ejecutar

Para ejecutar el playbook raspberrypi.yml que instala nginx, php, php5-fpm y mysql-server hay que entrar en la carpeta donde quedo el repositorio clonado y luego ejecutar el comando ansible-playbook con sudo tal como se muestra en las siguientes lineas.

cd RaspberryPi-Ansible
sudo ansible-playbook raspberrypi.yml -i inventario.yml
