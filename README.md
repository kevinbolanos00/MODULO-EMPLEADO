# empleado

![image](https://github.com/kevinbolanos00/empleado/assets/125316771/5c545491-e7ec-4766-b0ee-7cb9c8bb076c)

Módulo de Gestión de Empleados
Este proyecto consiste en un módulo de gestión de empleados, diseñado para facilitar la administración de información relacionada con los empleados, incluyendo sus respectivos cargos, departamentos, habilidades y datos personales.

Características
Creación y gestión de empleados: Permite agregar nuevos empleados, asignarles cargos, departamentos y registrar sus habilidades e información personal detallada.

Interfaz de usuario moderna: Utiliza el framework frontend FoundationCSS para proporcionar una interfaz de usuario intuitiva y atractiva.

Backend robusto: Desarrollado en Python utilizando el framework Django

Base de datos: Emplea PostgreSQL como sistema de gestión de bases de datos, garantizando un almacenamiento eficiente y seguro de la información.

Despliegue en la nube: La aplicación está desplegada en un servidor Ubuntu en Amazon EC2, utilizando herramientas como Nginx, Gunicorn y Supervisor para asegurar un rendimiento óptimo y acceso desde cualquier lugar.
Despliegue:
El despliegue se ha realizado en una instancia de Amazon EC2 con Ubuntu Server. Para garantizar un servicio web robusto y de alto rendimiento, se han utilizado las siguientes herramientas:
Nginx: Como servidor web y proxy inverso.
Gunicorn: Como servidor de aplicaciones WSGI para Django.
Supervisor: Para gestionar los procesos de Gunicorn y mantener la aplicación en funcionamiento continuo.
