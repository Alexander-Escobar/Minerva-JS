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
MinervaJS is a JSON declarative application platform designed to quickly and consistently create data-centric applications.
</p>
<p align="center">
  <img src="https://img.shields.io/npm/v/@minervajs">
  <img src="https://img.shields.io/npm/l/@minervajs">
  <img src="https://img.shields.io/node/v/@minervajs">
  <img src="https://img.shields.io/npm/dm/@minervajs">
</p>

It allows developers, analysts, and students to create applications from a declarative data model, defined in JSON, from which the platform can generate APIs, database access, and application interfaces.

MinervaJS seeks a Data-First workflow, which allows the rapid creation of CRUD-based systems with a structured and extensible architecture.

The Minerva Development Environment implements the JavaScript language on both the server and client sides, allowing users, students, analysts, and programmers to build an application based on a sound database analysis and design for storing the data and to carry out their project. Minerva JS is a development and learning tool for its creators that allows them to implement CRUD operations on tables in a matter of minutes.

Minerva-JS is a development environment that allows you to create applications of low to medium complexity in minutes, starting from a new or pre-existing relational database. It uses a manifest of the database objects that functions as the data model.


# Philosophy

MinervaJS is based on a simple principle:

```
The [application] is defined by its [data model]
```
Instead of writing large amounts of application code, developers define:

* entities
* relations
* validations
* metadata
* behaviors
* within an application model declared in JSON .

The platform interprets this model and exposes the services automatically, thus detaching itself from the problems of FrontEnd and BackEnd development, focusing exclusively on Database Design.

<p align="center">
All of the above under a "keep it simple" approach.
</p>



# Basic Concepts
JSON Application Template

The application is defined using a JSON structure that describes:

* Entities
* Records, Fields or Columns and Tuples
* Relations
* Restrictions
* metadata
* Behaviors

Example of ***the application model declared in JSON*** 

- models
  - tables[]
    - name
    - title
    - table
    - primary_key[]
    - sql_select
    - sql_edit
    - sql_new
    - sql_delete
    - toolbar[]
      - button
      - title
      - icon
      - URL
      - verbo
    - columns[]
      - col
      - type
      - length
      - minLength
      - required
      - visible
      - searchable
      - label
      - validations...


Advantages:

* Ideal for creating an application prototype or for school/university-type developments
* You can develop a medium or low complexity application in a matter of minutes, starting from a pre-existing and well-designed database.
* Implement a REST API on a pre-existing database.
* It is a lightweight development that can be implemented on almost any server with minimal resources
* Intuitive and attractive user interface for end users, easily customizable by applying knowledge of bootstrap and/or css
* Most API service responses have been implemented and standardized (e.g., 2xx: Success, 3xx: Redirection, 4xx: Client Error, 5xx: Server Error)


Disadvantages:

* It requires a high level of database design expertise if you want to implement a complex system
* Security levels are questionable and it is recommended to implement it on an intranet or internal network behind a firewall
* The format of the REST API is strict.
* Minerva JS works with the verbs GET/POST/PUT/DELETE; any other verb requires its own implementation.
* It is NOT recommended for use in applications that store sensitive or important information for the user.
* It is NOT recommended for use in applications that have a highly complex database design or structures that do not apply the relational model.


System Requirements, in Google Cloud Platform cloud environments:

* f1-micro (N1 first Generation)
* ubuntu 14.04 LTS (16)
* Allow HTTP traffic
* Standard Disk (10 GB)



## 📄 Licencia

BSD-2-Clause

