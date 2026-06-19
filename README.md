istema Web de Registro de Estudiantes con Flask y almacenamiento en JSON

Este proyecto consiste en una aplicación web desarrollada con el framework Flask de Python, orientada a la gestión básica de información de estudiantes. Su objetivo principal es permitir el registro, almacenamiento, 
visualización y eliminación de datos mediante una interfaz sencilla, utilizando un archivo JSON como sistema de persistencia en lugar de una base de datos tradicional.

La aplicación está estructurada siguiendo el modelo cliente-servidor. En el lado del cliente, se utilizan tecnologías web estándar como HTML y CSS para construir la interfaz de usuario, incluyendo un formulario
de registro y una tabla donde se muestran los datos almacenados. También se emplea JavaScript de forma básica para mejorar la interacción en la página.

En el lado del servidor, Flask se encarga de manejar las rutas, procesar las solicitudes del usuario y gestionar la lógica de la aplicación. Cuando un usuario envía el formulario, los dato
s se reciben en el backend, se procesan y se almacenan en un archivo llamado datos.json. Este archivo actúa como una base de datos ligera, permitiendo conservar la información incluso después de cerrar la aplicación.

Uno de los puntos clave del proyecto es la implementación de operaciones CRUD (Create, Read y Delete principalmente). Los estudiantes pueden ser añadidos mediante el formulario, consultados en una tabla dinámica
generada desde el JSON, y eliminados individualmente mediante enlaces o botones que envían la solicitud correspondiente al servidor.

El uso de JSON como almacenamiento permite entender de forma clara cómo se estructuran los datos en formato clave-valor, facilitando el aprendizaje de conceptos
fundamentales antes de pasar a bases de datos más complejas como MySQL o PostgreSQL.

Este proyecto está pensado con fines educativos, especialmente para estudiantes que están iniciando en el desarrollo web con Python.
Permite comprender la conexión entre frontend y backend, el manejo de rutas en Flask, y la manipulación de archivos para persistencia de datos.

En conclusión, esta aplicación representa una base sólida para proyectos más avanzados, ya que introduce conceptos esenciales del desarrollo web moderno de manera simple, práctica y funcional.
