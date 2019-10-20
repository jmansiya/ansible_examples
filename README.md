Ejemplos simples de playbooks de ansible

Para ejecutar estos playbook primero debemos tener instalado ansible en nuestro entorno de trabajo.

Una vez que tenemos instalado playbook en nuestro entorno de trabajo podemos ejecutar lo siguiente para comprobar que está correctamente instalado:

 ansible --version.

Para lanzar nuestros playbooks usaremos las siguientes instrucciones:

 - ansible-playbook PlayBookIncludeExample.yml -i inventory.txt
 - ansible-playbook httpsPlaybook.yml -i inventory.txt 

 Ansible Project roles example:
 - ansible-playbook setup_application.yml -i inventory.txt

 Documentación oficial de ansible: https://docs.ansible.com/