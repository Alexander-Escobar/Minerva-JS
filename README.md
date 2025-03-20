# Minerva-JS
El Entorno de Trabajo Minerva implementa el lenguaje JavaScript tanto del lado del servidor como del cliente, permite a usuarios/estudiantes/analistas/programadores, levantar un aplicativo partiendo de un buen Analisis y Diseño de base de datos para el alojamiento de la informacion del mismo y llevar a cabo su proyecto. Minerva JS, es una herramienta para el desarrollo y aprendizaje de sus creadores que permite implementar en cuestion de minutos CRUD sobre tablas.

***Minerva-JS, es un entorno de trabajo que permite crear aplicaciones de mediana o poca complejidad en minutos, partiendo de una base de datos Relacional nueva o pre-existente. Empleando un manifiesto de los objetos de la base de datos que funciona como el Modelo de Datos.***

Filosofia:
La filosofia de Minerva JS, es desarrollar en forma rapida, ligera y en cierta medida de uso Intuitivo un aplicativo que permita a los Analistas/Diseñadores de Base de datos, desvincularse de los problemas del desarrollo del FrontEnd y BackEnd, enfocandose exclusivamente en el Diseño de la Base de Datos. Todo lo anterior bajo un enfoque de "mantenlo simple".

Ventajas:
* Ideal para creacion de un prototipo de aplicacion o para desarrollos de tipo escolar/universitario
* Puedes desarrollar una Aplicacion de Mediana o Baja Complejidad en cuestios de Minutos, partiendo de una base de datos pre-existente y bien diseñada.
* Implementar una API REST, sobre una Base de datos pre-existente.
* Es un desarrollo ligero y que puede ser implementado en casi cualquier servidor con minimos recursos
* Interfaz para usuarios finales, intuitiva y atractiva, de gran facilidad de personalizacion aplicando conocimientos en bootstrap y/o css
* Se han implementado y estandarizado la mayoria de respuestas del servidio de API (Ej: 2xx: Exito, 3xx: Redireccion, 4xx: Error del cliente, 5xx: Error del Servidor)

Desventajas:
* Requiere alto nivel de dominio de diseño de Base de datos, si desea implementar un sistema complejo
* Los niveles de seguridad son cuestionables y se recomienta ser implementado en una intra-net o red interna bajo un firewall
* El formato de la API Rest, es de caracter extricto
* Minerva JS, trabajo con los verbos GET/POST/PUT/DELETE, cualquier otro verbo requiere su propia implementacion.

* NO se recomienta utilizar para Aplicaciones que almacenaran informacion Sensitiva o de importancia para el usuario.
* NO se recomienda utilizar para Aplicaciones que tienen un diseño de base de datos Altamente complejo o estructuras que no aplique el modelo-relacional

Requerimientos del Sistema, en ambientes en la nube de Google Cloud Platform:
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
