# Minerva-JS
Framework Minerva JavaScript, permite a estudiantes, que han realizado un buen Analisis y Diseño para el alojamiento de los datos de un aplicativo, llevar a cabo su proyecto. Minerva JS, es una herramienta para el desarrollo y aprendizaje que permite crear en cuestion de minutos CRUD sobre tablas.

Filosofia:
La filosofia de Minerva JS, es desarrollar en forma rapida, ligera y en cierta medida de uso Intuitivo un aplicativo que permita a los Analistas/Diseñadores de Base de datos, desvincularse de los problemas del desarrollo del FrontEnd, trabajando en un diseño de Base de Datos, exclusivamente para el almacenaje de informacion.

Ventajas:
* Ideal para creacion de un prototipo de aplicacion o para desarrollos de tipo escolar/universitario
* Puedes desarrollar una Aplicacion de Mediana o Baja Complejidad en cuestios de Minutos, partiendo una base de datos pre-existente y bien diseñada.
* Implementar una Api REST, sobre una Base de datos pre-existente.
* Es un desarrollo ligero y que puede ser implementado en casi cualquier servidor con minimos recursos
* Interfaz para usuarios finales, intuitiva y atractiva, de gran facilidad de personalizacion aplicando conocimientos en bootstrap o css
* Se han implementado y estandarizado la mayoria de respuestas del servidio de API (Ej: 2xx: Exito, 3xx: Redireccion, 4xx: Error del cliente, 5xx: Error del Servidor)

Desventajas:
* Requiere alto nivel de dominio de diseño de Base de datos
* Los niveles de seguridad son cuestionables y se recomienta ser implementado en una intra-net o red interna bajo un firewall
* El formato de la API Rest, es de caracter extricto
* Minerva JS, trabajo con los verbos GET/POST/PUT/DELETE, cualquier otro verbo requiere su propia implementacion.

* NO se recomienta utilizar para Aplicaciones que almacenaran informacion Sensitiva o de importancia para el usuario.
* NO se recomienda utilizar para Aplicaciones que tienen un diseño de base de datos complejo o estructuras que no aplique el modelo-relacional

Requerimientos de Sistema, Creacion del Servidor en Google Cloud Platform:
* f1-micro (N1 primera Generacion)
* ubuntu 14.04 LTS (16)
* Permitir trafico HTTP
* Disco Estandar (10 GB)

Tecnologia Implementada
* NodeJs
* ExpressJS (Como servidor de Paginas Web)

Listado de Dependencias:
* "express": testeado "4.16.4", 4.17.1
* "nodemailer": testeado "6.3.0", 6.4.11
* "stringbuilder": "0.0.11"



