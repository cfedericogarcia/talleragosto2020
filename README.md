TALLERAGOSTO2020	

=========
Se crea este playbook con Ansible con el fin de instalar los paquetes que corresponden al servidor web (Apache y PHP)
Generar un ViartualHost a través de un template.
Configuración de Firewall y Servicios.


Requirements
------------
Es necesario tener configurado la clave publica/privada para poder acceder por ssh desde el controller  a los equipos que se van a controlar. 
Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Roles 
--------------
Se crearon los roles:
apache-centos: (Instala y configura apache en los sistemas de Red-Hat)
apache-ubuntu: (Instala y configura apache en los sistemas Debian)
php-centos: (Instala y configura php en los sistemas Red-Hat)
php-ubuntu: (Instala y configura php en los sistemas Debian)

Author Information
------------------

Nicolas Isnardi - 189027
Federico García - 188244
