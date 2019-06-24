# guacamole 1.0.0 script install CentOs7
Este script de instalacion de Guacamole 1.0.0 esta probado en Centos 7 junto con MySQL y Tomcat. 
**_Es muy facil instalar. :)_**

El script trabaja en una instalacion limpia de Centos 6/7 e instala Guacuamole 1.0.0 con autenticacion local del usuario.

Las tareas que reealiza son:
- [x] Instala lso paquetes de dependencia
- [x] Descarga Guacamole y MySQL Connector packages
- [x] Instala Guacamole Server
- [x] Instala Guacamole Client
- [x] Instala MySQL Connector
- [x] Configura MariaDB o MySQL
- [x] Configura FirewallD o Iptables
- [x] Configura Tomcat Server
- [x] Genera los Java KeyStore para SSL Support

Asumiento que tu estas logueados como **root**, hacer la instalacion de Wget :
```sh
yum install -y wget
```
Luego debemos de descargar el script usando el Wget la version de 1.0.0 :
```sh
wget -q https://raw.githubusercontent.com/handblack/guacamole/master/guacamole-1.0.0-install-script.sh
```
o tambien puedes usar la vesion de 0.9.14
```sh
wget -q https://raw.githubusercontent.com/handblack/guacamole/master/guacamole-0.9.14-install-script.sh
```

Ahora tenemos que asignar el atributo de Execute al script :
```sh
chmod +x guacamole*
```
Ahora ejecutamos el script que hemos descargado  :)
```
./guacamole-1.0.0-install-script.sh
```
