# comandos-linux
Bitácora de comandos linux, visto en el cuatrimestre de Sistemas Operativos

Comando | Descripción | Ejemplo
-----|------|-----
ip addr | Interfaces de red que tiene la maquina | ip addr > ip de tu computadora
ping 8.8.8.8 | Muestra paquetes recibidos y perdidos | ping 8.8.8.8 > muestra los paquetes, latencia y ms de tu internet
sudo|Dar permisos de administrador para descargar paquetes o programas|sudo dkpg -i google-chrome-stable_current_amd64.deb
apt|Permiso de descargar paquetes|sudo apt install python3
install|Instala paquetes|sudo apt install python3
cd|Moverse en los directorios|cd Descargas/
cd..|Retroceder un directorio|cd.. Descargas/
ls|Lista de los archivos en un directorio|achavarrig611@ubuntu-ulacit ~$ ls > muestra el contenido del directorio
dpkg|Instala paquetes|dpkg -i google-chrome-stable_current_amd64.deb
update|Actualiza lista de paquetes disponibles|sudo apt-get update
upgrade|Mejora lista de paquetes disponibles|sudo apt upgrade
pwd|Imprime donde se encuentra uno en un directorio|pwd > home/achavarrig611
cmatrix|Paquete que puede mostrar codigos que se muestran en la pelicula matrix|sudo apt install cmatrix
neofetch|Información de tu ordenador que lo muestra en la terminal|sudo apt install neofetch > neofetch >  muestra la informacion de tu ordenador
whoami|Muestra quien es en el ordenador|whoami > achavarrig611
man|Muestra el manual de un comando|man sudo
sudo su o su root |Ir de forma root|sudo su / su root
exit|Salir de la terminal|exit
sudo useradd [user] -m |Añadir un usuario | sudo useradd NeO -m 
nano|Bloc de notas| nano > 123.txt
cat|Leer datos y mostrar su contenido de ello|cat /var/log/syslog
tail|Mostrar partes de un comando|tail -n 10 /var/loh/syslog
head|Mostrar la parte principal de algun documento|head -n 10 /var/log/syslog | more
cat more |Muestra mas contenido del comando que queremos capturar|cat /var/log/syslog | more 
