<p align="right">
  <a href="./README.md">
    <img src="https://img.shields.io/badge/🇪🇸-Español-red" alt="Español">
  </a>
  <a href="./README.en.md">
    <img src="https://img.shields.io/badge/🇺🇸-English-blue" alt="English">
  </a>
</p>

<h1 align="center">
  MinervaJS
</h1>

<p align="center">
MinervaJS es una plataforma de aplicaciones declarativas JSON diseñada para crear aplicaciones centradas en datos de forma rápida y consistente.
</p>
<p align="center">
  <img src="https://img.shields.io/npm/v/@minervajs">
  <img src="https://img.shields.io/npm/l/@minervajs">
  <img src="https://img.shields.io/node/v/@minervajs">
  <img src="https://img.shields.io/npm/dm/@minervajs">
</p>

Permite a desarrolladores, analistas y estudiantes crear aplicaciones a partir de un modelo de datos declarativo, definido en JSON, a partir del cual la plataforma puede generar API, acceso a bases de datos e interfaces de aplicación.

MinervaJS busca un flujo de trabajo Data-First, lo que permite la creación rápida de sistemas basados en CRUD con una arquitectura estructurada y extensible.

El Entorno de Trabajo Minerva implementa el lenguaje JavaScript tanto del lado del servidor como del cliente, permite a usuarios/estudiantes/analistas/programadores, levantar un aplicativo partiendo de un buen Analisis y Diseño de base de datos para el alojamiento de la informacion del mismo y llevar a cabo su proyecto. Minerva JS, es una herramienta para el desarrollo y aprendizaje de sus creadores que permite implementar en cuestion de minutos CRUD sobre tablas.

Minerva-JS, es un entorno de trabajo que permite crear aplicaciones de mediana o poca complejidad en minutos, partiendo de una base de datos Relacional nueva o pre-existente. Empleando un manifiesto de los objetos de la base de datos que funciona como el Modelo de Datos.

# Filosofía

MinervaJS se basa en un principio simple:

```
La [aplicación] se define por su [modelo de datos]
```

En lugar de escribir grandes cantidades de código de aplicación, los desarrolladores definen:

* entidades
* relaciones
* validaciones
* metadatos
* comportamientos

dentro de un **modelo de aplicación declarada en JSON**.

La plataforma interpreta este modelo y expone los servicios automáticamente. desvinculandose asi de los problemas del desarrollo del FrontEnd y BackEnd, enfocandose exclusivamente en el Diseño de la Base de Datos. 
<p align="center">
Todo lo anterior bajo un enfoque de "mantenlo simple".
</p>



# Conceptos Básicos
Modelo de Aplicación JSON

La aplicacion es definida usando una estructura JSON que describe:

* Entidades
* Registros, Campos o Columnas y Tuplas
* Relaciones
* Restricciones
* metadata
* Comportamientos

Ejemplo del **modelo de aplicación declarada en JSON**


models
└── tables[]
    ├── name
    ├── title
    ├── table
    ├── primary_key[]
    ├── sql_select
    ├── sql_edit
    ├── sql_new
    ├── sql_delete
    ├── toolbar[]
    │   ├── button
    │   ├── title
    │   ├── icon
    │   ├── URL
    │   └── verbo
    └── columns[]
        ├── col
        ├── type
        ├── length
        ├── minLength
        ├── required
        ├── visible
        ├── searchable
        ├── label
        └── validations...


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



## 📄 Licencia

BSD-2-Clause

