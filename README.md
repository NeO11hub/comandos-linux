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
head|Mostrar la parte principal de algun documento|head -n 10 /var/log/syslog pipe more
cat more |Muestra mas contenido del comando que queremos capturar|cat /var/log/syslog pipe more 
history|Ver el historial|history
install|Instala programas|sudo snap install spotify
start|Empezar un proceso|sudo service apache2 start
free -h|Cantidad de memoria y te dice la memoria swap que tiene el sistema|free -h
swapon|Te dice donde esta el archivo de swap|swapon
df -h |Sirve para ver todos los discos que tiene conectados en el disco|df -h
mount|Sirve para montar discos o datos|sudo mount -t tmpfs -o size=1024m new_ram_disk /mnt/ram_disk
chmod|Cambia los permisos de las carpetas|chmod 777
chmod + [tuScript]|lee, escribe y ejecuta|chmod +x 777
chmod -x [tuScript]|Quita los permiso de ejeccución|chmod -x [tuScript]
ls -l|Muestra la lista de permiso de los archivos|ls -l
du -h|Tamaño de archivo|du -h txt.txt
stat|Fecha de creación|stat txt.txt
touch|actualiza la hora de fecha de modificacion y crea un archivo de texto|touch > archivo.txt
chwon|Toma posesion de un archivo|chwon [archivo]
file|muestra el formato de un archivo|file pdf.pdf
df -h|Muestra los false system del sistema|df- h
mount|Monta cierto dispositivos|mount disk1
Gparted|Administra las partes del disco duro del sistema|Gparted
kill -9 $PID|Mata un proceso|kill -9 $PID Firefox
ps -aux|Para ver todos los IDS de los programas o los procesos|ps -aux 
grep|Mostrar localizacion de los procesos|grep -help
pwd|Te muestra donde esta uno y en que ruta|pwd > achavarrig611/home
docker ps -a|Es para ver los contenedores|docker ps -a
docker run|Corre el docker en un contenedor en un puerto localhost que en este caso es 8080|docker run -d -p 8080:80 nextcloud
docker push|Añade un contenedor|docker push nextcloud
docker commit|Convierte un contenedor en una imagen|		docker commit (ID del contenedor) [nombre amigale] 498409123902	  mortasoft/ubuntu-calc
docker login -u|Accede a un usuario en especifico| docker login -u achavarrig611
docker pull|Comienza a descargar un contenedor|docker pull mortasoft/ubuntu-calc
docker run it|Es para comenzar un contenedor|docker run it [archivo]
docker stop|Apaga un contenedor|docker stop [ID del contenedor]
scp|Hacer una copia de una red|scp text.txt  mortasoft@[ip de la maquina]:/home/mortasoft/Semana09/texto3.txt 
wget|Extraer archivos de una pagina web|wget [url]
cp|Copia un documento o archivo de texto|cp texto.txt texto2.txt
mv|Mueve directorios o documentos|mv texto2.txt /tmp
ls/tmp|Selecciona el contendio y busca una cadena de texto en dicho directorio|ls /tmp pipe grep texto2.txt
rm|Quita un archivo|rm /tmp/texto2.txt
rm [archivo] -R |Quita una carpeta|rm [prueba] -R
rm [prueba] -Rf|Forzar que quite la carpeta|rm [prueba] -Rf
git clone|Comando para descargar repositorios github|git clone https://github.com/mortasoft/linux-scripts
curl|Envia datos a la paginas web|curl -X GET -L [URL]
--------|Comando para archivos|--------
wc|Contea palabras|wc /var/log/syslog -l --> lines
more /var/log/syslog|Muestra por paginas el contenido pero con mas contenido por el more|more /var/log/syslog
less /var/log/syslog|Muestra por paginas el contenido pero con mas contenido por el less|less /var/log/syslog
ls -l / -R |Muestra todo lo del escritorio todo lo que tiene|ls -l / -R 
grep|Busca una cadena de texto|grep -r "linux" /var/log/syslog
grep -r "linux" /var/log/syslog|Busca el texto linux en la carpeta /var/log/syslog pero dentro de los archivos.|grep -r "linux" /var/log/syslog 
find|Busca un archivo|find /home/mortasoft -name index.html
history pipe grep curl|Busca en el historial si hay una palabra curl|history pipe grep curl
reboot|Reinicia el equipo|reboot
shutdown|Apaga el equipo|shutdown
pdunite|Une pdfs|pdfunite [pdf que quiere poner] [nombre del pdf unido] 01.pdf 02.pdf 03.pdf  salida.pdf
pdfseparate -f|Separa pdfs|pdfseparate -f [numero de la pdf] -l 5 [nombre del archivo unido] [nombre del pdf final] 1  salida.pdf   resultado_%d.pdf
sudo apt-get install ocrfeeder tesseract-ocr tesseract-ocr-spa para instalarlo


