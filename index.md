---
layout: default
---
# Pract01-IaaS-DSI
## Informe de la primera Práctica 1
Después de conectarse a la VPN de la ULL y de conectarse a la Consola VNC, cambiaremos la contraseña, y averiguaremos la IP asignada. La IP asignada es 10.6.130.187 y la usaremos para conectarse por SSH a la máquina virtual.

![image](https://github.com/user-attachments/assets/c13c20cf-4a87-49bb-9a50-5f3368be248d)


El siguiente paso será modificar el nombre del host; de usuario@ubuntu a usuario@iaas-dsi. Para luego reiniciar la máquina virtual mediante el comando sudo reboot.

![image](https://github.com/user-attachments/assets/8af8505e-956b-488b-9bbd-8c2e049b3e13)

Una vez hecho esto, configuraremos la infraestructura de la clave pública-privada.

![image](https://github.com/user-attachments/assets/b92b539e-98d0-4b1c-89f3-cdb4e6185e40)

Para luego copiarla a la máquina virtual.

![image](https://github.com/user-attachments/assets/b7f6c76f-d1d1-44fe-8f56-b04ea517c354)

Una vez hecho esto probamos a iniciar sesión simplemente con el nombre del usuario.

![image](https://github.com/user-attachments/assets/91bd30ba-4595-4173-8f54-ee914da0f4c1)

Después de haber realizado estas configuraciones. Procederemos a instalar git y Node.js en la máquina virtual del IaaS. Usaremos el comando sudo apt install git para instalar git, como el comando sugiere. También configuraremos el nombre del usuario, y el gmail. Luego usaremos git config --list para asegurarnos de que lo hemos hecho bien.

![image](https://github.com/user-attachments/assets/6675deb1-c67c-44d8-af38-2bfe0bd50d15)

Continuaremos con la configuración del prompt de la terminal para que aparezca la rama actual en la que nos encontramos cuando accedemos a algún directorio que resulta estar asociado a un repositorio git. Descargaremos un script de git prompt y modificaremos el bashrc para poder llevar la tarea a cabo. Tras realizar esto, haremos visible la clave pública de la máquina virtual para enlazarla con el repositorio github propio.


![image](https://github.com/user-attachments/assets/dc295f21-d425-4781-93e8-87bb981ff4b6)

![image](https://github.com/user-attachments/assets/45bbe74d-7b07-48db-8eda-41afeaf9fea6)

(poner foto de github aquí)

Hecho esto procederemos a clonar el repositorio en la máquina virtual; para luego comprobar si está dentro de la máquina virtual y colocarnos en su directorio, con los comando ls y cd respectivamente. En las imágenes siguientes se puede ver como la instalación de git se ha hecho correctamente.

![image](https://github.com/user-attachments/assets/dcdb6435-1721-4f40-9c67-ab571654d7b8)

![image](https://github.com/user-attachments/assets/af6d483f-4a8c-4852-8d62-2e69b52ba8a6)


Ahora procederemos a instalar Node.js.

![image](https://github.com/user-attachments/assets/d03b7f27-579a-4a05-b630-67b601ed94bd)


Además, usaremos el comando nvm install node para conseguir la versión más reciente del programa.

![image](https://github.com/user-attachments/assets/77a93b47-eabc-4577-9068-a507737b3a84)


Finalmente, confirmaremos las versiones instaladas en el sistema. 

![image](https://github.com/user-attachments/assets/82e88031-becf-4856-baae-e968c382d33d)

