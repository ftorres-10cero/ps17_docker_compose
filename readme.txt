
PRESTASHOP:

Prestashop requeire mysql para su funcionamiento.

Este Docker Compose contiene los dos servicios.



DESPLIEGUE:

Para desplegar prestashop 17 usar el comando

	> docker-compose up

Esto muestra en el terminal toda la secuencia de arranque

Para una llamada diferida:

	>docker-compose up -d


El proceso tarda unos minutos, especialmente con el despliegue inicial.

Se ha configurado para que los volumenes se creen de forma local dentro de la carpeta

	/prestashop -> contenido de prestashop
	/modules -> contenido de la carpeta de módulos
	/db_data -> contenido de las bases de datos


USO:

La web se despliega en: 
	http://localhost:8082

Se requiere proceso de instalación convencional y la instalación de los módulos necesarios.






