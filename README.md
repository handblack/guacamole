# guacamole 1.0.0 script install CentOs7
Este script de instalacion de Guacamole 1.0.0 esta probado en Centos 7 junto con MySQL y Tomcat. 
**_Es muy facil instalar. :)_**

El script trabaja en una instalacion limpia de Centos 6/7 e instala Guacuamole 1.0.0 con autenticacion local del usuario.

Las tareas que reealiza son:
-[X]Install Packages dependencies
[X]Download Guacamole and MySQL Connector packages
[X]Install Guacamole Server
[X]Install Guacamole Client
[X]Install MySQL Connector
[X]Configure MariaDB or MySQL
[X]Configure FirewallD or Iptables
[X]Setting Tomcat Server
[X]Generates a Java KeyStore for SSL Support

Asumiento que tu estas logueados como **root**, hacer la instalacion de Wget :
```sh
yum install -y wget
```
Luego debemos de descargar el script usando el Wget :
```sh
wget -q https://github.com/handblack/guacamole/blob/master/guacamole-install-script.sh
```
Ahora tenemos que asignar el atributo de Execute al script :
```sh
chmod +x guacamole-install-script.sh
```
Ahora ejecutamos el script  :)
```
./guacamole-install-script.sh
```
