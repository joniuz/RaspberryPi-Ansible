# RaspberryPi-Ansible
Coleccion de scripts Ansible que permiten la instalacion de una Raspberry Pi - IoT Server desde cero

Para instalar los pasos son
1. Realizar un update (siempre es recomendable)

sudo apt-get update

2. Instalar Ansible

sudo apt-get install ansible

3. Instalar git

sudo apt-get install git

4. Clonar el repositorio

git clone https://github.com/internetdelascosas/RaspberryPi-Ansible.git

Para ejecutar el playbook ejecutar

cd RaspberryPi-Ansible
sudo ansible-playbook raspberrypi.yml -i inventario.yml
