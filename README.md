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






