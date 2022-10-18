<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->

<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->


[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">

  <p align="center">
    Tecnical Test Mercado Libre!
    <br />
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Tabla de contenido</summary>
  <ol>
    <li>
      <a href="#sobre-el-proyecto">Sobre el proyecto</a>
      <ul>
        <li><a href="#construido-con">Construido con</a></li>
      </ul>
    </li>
    <li>
      <a href="#pre-requisitos">Pre-Requisitos</a>
      <ul>
      <li><a href="#empecemos">Empecemos</a></li>
      </ul>
    </li>
     <li><a href="#consideraciones">Consideraciones</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## Sobre el proyecto

[![Product Name Screen Shot][product-screenshot]](https://example.com)

Este proyecto fue construido siguiendo las instrucciones de Mercado Libre para la evaluación técnica. Se implementó una arquitectura de micro-servicios y traté de llevar las mejores prácticas, solucionando inconvenientes y adaptandome a mi realidad de tiempo acotado. 

Implementé tests solo en un  microservicio, para mostrar el conocimiento sobre los mismos y al mismo tiempo alcanzar el objetivo en el tiempo estipulado. 

También se hizo uso de una libreria de logs para integrar la lógica de trazabilidad. 

En cuento al front-end se usó como referencia la página de MELI, de hecho, se descargó el CSS y lo adapté a lo que necesitaba. Mis conocimientos en esta área, como ya se lo había mencionado antes, no es muy amplio. Di mi mejor esfuerzo y aunque según lo investigado hay mejores herramientas, como Material UI, realmente no tenía el tiempo para implementarlo, así que seguí el enfoque tradicional con ReactJS, CSS puro y usando algunos componentes de Material UI (en paginado y botones).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Construido Con

Librerias y frameworks utilizados.

* [![React][React.js]][React-url]
* [![NestJs]][React-url]
* [![Quarkus]][quarkus-url]
* [![Vertx]][vertx-url]
* [![Java]][java-url]
* [![Node]][node-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>


### Pre-Requisitos

Es solo necesario tener instalado docker dejo la pagina de instalacción
[Docker][docker-url]

<!-- GETTING STARTED -->
## Empecemos
Para descargar e inicializar el proyecto seguir las siguientes instrucciones. 
* git clone
  ```sh
  git clone https://github.com/willandher/ml-compose.git
  ```
* Ingresar al  a la carpeta
  ```sh
  cd ml-compose
  ```  
* git submodule init
  ```sh
  git submodule init
  ```
* git submodule update
  ```sh
  git submodule update
  ```
* git submodule foreach git checkout main
  ```sh
  git submodule foreach  git checkout main
  ```
* Docker-compose run
  ```sh
  docker-compose build && docker-compose up
  ```
* Para ver el proyecto ir a la siguiente url (Esperar que el docker termine [finish])
* 
  ```sh
  http://localhost:9017
  ```



<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- LICENSE -->
## Consideraciones
Quisiera comentarles que este desafío me hizo salir de mi zona de confort; realmente tenía mucho tiempo sin ver front-end y tuve que ponerme  al día. Me encantó reactjs y sé que aún me falta mucho por aprender. Estuve leyendo un montón y viendo videos para entender cuál es la filosofía de esta librería y creo que ya puedo decir que entiendo mucho mas que hace 1 semana. Entre cosas también hice el BackEnd-For-FrontEnd en Java utilizando un framework reactivo, llamado quarkus, y no hay una razón específica solo queria dejar un poco más claro en todas las herramientas que me puedo desenvolver. 
Por otro lado, quisiera dejar una lista de cosas que me hubiera gustado ver de otra forma o mejorar, tales como: 
* Hacer un mejor manejo de los errores, utilizando interceptores en nest al igual que en quarkus.
* Crear IDs de seguimientos de logs desde el front-end hasta el back-end para poder ver la trazabilidad de las peticiones. 
* Organizar un poco mejor las carpetas en el front-end. 
* Hacer tests en el Front-End. 
* Tambien deje los .env en los proyectos, solo para efectos de prueba, se que es una mala practica. 




<!-- CONTACT -->
## Contact

Willandher Goyo willandherg@gmail.com
Por favor considerar que estaré de vacaciones desde el 21 de octubre hasta el 4 de noviembre, si por algún motivo no les contesto alguna llamada por favor escribirme un mail, a veces la señal no es muy buena en el sur  :) Muchas gracias por la oportunidad. 

<p align="right">(<a href="#readme-top">back to top</a>)</p>








[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/willandher-goyo-65a551bb/
[product-screenshot]: images/diagrama.png
[finish]: images/finish.png
[NestJs]: https://img.shields.io/badge/Nestjs-Nestjs-green
[Quarkus]: https://img.shields.io/badge/Quarkus-Quarkus-yellow
[quarkus-url]: https://quarkus.io/
[Vertx]: https://img.shields.io/badge/Vertx-Vertx-red
[vertx-url]: https://vertx.io/
[Node]: https://img.shields.io/badge/Node-Node-4FC08D
[node-url]: https://nodejs.org/en/
[Java]: https://img.shields.io/badge/Java-Java-61DAFB
[java-url]: https://jdk.java.net/11/
[docker-url]:https://www.docker.com/ 
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/


