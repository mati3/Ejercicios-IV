## Tema 4

**Ejercicio 1:**

Instala LXC en tu versión de Linux favorita. Normalmente la versión en desarrollo, disponible tanto en GitHub como en el sitio web está bastante más avanzada; para evitar problemas sobre todo con las herramientas que vamos a ver más adelante, conviene que te instales la última versión y si es posible una igual o mayor a la 1.0.

Para la instalación de lxc hemos seguido el siguiente [tutorial](https://manuelfrancoblog.wordpress.com/2017/09/18/lxc-primeros-pasos/)

![imagen](Imagenes/lxc.png)

Hemos tenido que instalar los siguiente paquetes:

		Sudo apt install lxc -y
		Sudo apt-get install openssl-server

Una vez instalado comprobamos que todo está bien configurado, sale todo enable en verde, por lo tanto todo ok.

![imagen](Imagenes/Captura_08.png)

**Ejercicio 2:**

Crear y ejecutar un contenedor basado en tu distribución y otro basado en otra distribución, tal como Fedora. Nota En general, crear un contenedor basado en tu distribución y otro basado en otra que no sea la tuya.

Creamos un contenedor ubuntu :

![imagen](Imagenes/Captura_01.png)

![imagen](Imagenes/Captura_02.png)

Creamos otro contenedor gentoo y le damos el nombre de centos.

![imagen](Imagenes/Captura_04.png)

![imagen](Imagenes/Captura_05.png)

Listamos los contenedores

![imagen](Imagenes/Captura_06.png)

Arrancamos ubuntu y mostramos la información del contenedor:

![imagen](Imagenes/Captura_07.png)

**Ejercicio 3**

Instalar docker.

