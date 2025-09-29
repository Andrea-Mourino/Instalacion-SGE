## PASO 1
### Instalacion Apache2

<img width="1919" height="1076" alt="Captura desde 2025-09-29 09-49-23" src="https://github.com/user-attachments/assets/4ec8d562-14b2-4b56-b332-3c933522250f" />


Para saber si a funcionado correctamente buscamos en el navegador: http://localhost

<img width="1919" height="1076" alt="Captura desde 2025-09-29 09-53-51" src="https://github.com/user-attachments/assets/4e9c0529-6ed4-4913-8686-01482e0bf7ea" />


## PASO 2
### Instalar mysql

<img width="1919" height="1076" alt="imagen" src="https://github.com/user-attachments/assets/3fba5885-fc81-4061-86ca-6c090ef3144c" />


Para berificar que los cambios funcionan hacemos un sudo systemctl status mysql y deberia de verse algo asi

<img width="1919" height="1076" alt="imagen" src="https://github.com/user-attachments/assets/310f1ff1-e057-45bc-9b15-a1d80aa6753a" />


### PASO 3
## Instalacion PHP

<img width="1919" height="1076" alt="imagen" src="https://github.com/user-attachments/assets/9fea5abe-6c35-4d55-8542-d2bef725d22e" />


Instalamos php y el modulo para que apache pueda interpretar php y vemos si esta corriendo perfectamente

<img width="1919" height="1076" alt="imagen" src="https://github.com/user-attachments/assets/7cce10af-27d2-42dd-ad52-215261b9e17e" />


Con el comando sudo nano /var/www/html/info.php abrimos el archivo y escribimos "Prueba" y guardamos

<img width="1919" height="1076" alt="imagen" src="https://github.com/user-attachments/assets/0a022bf6-cb8f-4959-9dcf-8a1abe373cd7" />


## PASO 4
### Instalar phpMyAdmin para gestionar MySQL

<img width="1919" height="1076" alt="imagen" src="https://github.com/user-attachments/assets/0b5163fb-f5f0-4f96-936a-ee86493f8588" />


Entramos en mysql

<img width="1919" height="1076" alt="imagen" src="https://github.com/user-attachments/assets/f43e58f6-6ea1-4eae-b9f1-c839605766ab" />


ya abierto creamos la base de datos para wordpress

<img width="1919" height="1076" alt="imagen" src="https://github.com/user-attachments/assets/fc230d75-571a-40d6-a92c-53063d240ca4" />


Creamos un usuario y le damos permisos a la base de datos que acabamos de crear

<img width="1919" height="1076" alt="imagen" src="https://github.com/user-attachments/assets/4a9d0c97-0cc6-4b82-b96b-62aee6800129" />


y le damos \q para salir de mysql. Acto seguido instalamos phpmyadmin con sudo apt install phpmyadmin y deberia salir una ventana tal que asi

<img width="1087" height="345" alt="imagen" src="https://github.com/user-attachments/assets/1ded8cec-1c05-443d-a466-9b7a89773665" />


Aqui comprobamos que se a instalado correctamente y crear un enlace para poder acceder desde el navegador y comprobamos que se ha creado

<img width="1916" height="1075" alt="imagen" src="https://github.com/user-attachments/assets/88c1d3b8-b860-4196-a75d-e68f4ea55b80" />


entramos al navegador y escribimos localhost/phpmyadmin/

<img width="1916" height="1075" alt="imagen" src="https://github.com/user-attachments/assets/aafb7c65-1c4b-4b31-8fa0-ccaa5314a04a" />



## PASO 5
### Descargar e Instalar WordPress

Aqui vamos a la carpeta personalo y descargamos la ultima version de Wordpress y con el comando tar -xvzf latest.tar.gz descomprimimos el archivo

<img width="1916" height="1075" alt="imagen" src="https://github.com/user-attachments/assets/c93b6d42-1a4d-4ae2-8dbd-3d1c0267e0d3" />


A continuacion copiamos la carpeta de Wordpress a la carpeta raiz de apache, cambiamos el propietario y cambiamos los permisos de la carpeta

<img width="1916" height="1075" alt="imagen" src="https://github.com/user-attachments/assets/1a093e7e-3223-42f4-a66c-b04dbd2c39f1" />

Copiamos el archivo de configuracion de ejemplo
Editamos el archivo de configuracion

<img width="1916" height="1075" alt="imagen" src="https://github.com/user-attachments/assets/445333e0-18bd-4631-948a-70047a3fbc73" />





