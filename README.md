# PRÁCTICA DE AWS

<img width="1851" height="496" alt="imagen" src=https://github.com/user-attachments/assets/22891987-bc4b-453f-b315-54841b08c694>


## ÍNDICE
1. [Introducción](https://github.com/acuevasf04/Pr-ctica_AWS/edit/main/README.md#1--introducci%C3%B3n)
2. [CREACIÓN DE VPC]()
3. [CREACION DE INSTANCIAS]()
4. [ACCESO A LAS INSTANCIAS E INSTALACIÓN DE SERVICIOS]()

## 1.- INTRODUCCIÓN

En esta práctica vamos a aprender a como lanzar una página en la nube de AWS. El objetivo de esta práctica es aprender a usar la interfaz de Amazon, y crear servidores, y redes en dentro de esto.

## 2.- CREACIÓN DE VPC

La creación de las VPC sirven para que crear la estructura de toda la red que vamos a usar. Sus principales funciones son el aislamiento y control de tráfico de la red. También se pueden dividir en subredes y administrar si son públicas o privadas. 
Para conectar esta red con otra, lo que hay que hacer es configurar la tabla de enrutamiento y asignar las IPs que queremos que se asocien entre sí.

### CREACIÓN DE LAS VPCS

Para crear la VPC se primero se tiene que seleccionar el botón de ```Crear VPC``` para crear una nueva.

<img width="1851" height="496" alt="imagen" src="https://github.com/user-attachments/assets/1b80fcde-a5aa-4fc8-b0a5-3e417caa0e89" />

Teniendo en cuenta la estructura que se va a montar, se crearán 3 subredes distintas, una subred para la salida a internet, y las otras dos van a servir para alojar los servidores web, NFS y la base de datos, que en este caso usaré MariaDB. 

<img width="1857" height="861" alt="imagen" src="https://github.com/user-attachments/assets/41dc4fa3-3047-47a9-a3de-c5b86287bea8" />

Una vez creada la VPC, hay que crear las subredes, para asignarlas más tarde a las instancias que se crearán más adelante. Para comprobar que las subredes se han creado correctamente, 

<img width="1441" height="642" alt="imagen" src="https://github.com/user-attachments/assets/c5603e0a-94ff-46ca-92de-74c6cce16ab4" />

Ahora, en el menú de la izquierda hay que darle a la puerta de enlace para dar salida a internet. Se tiene que dar en el botón de nuevo gateway de Internet y a partir de ahí configurar la salida.

<img width="1838" height="655" alt="imagen" src="https://github.com/user-attachments/assets/08c24c12-5a09-4ca8-b4cf-89e1d9253827" />

Una vez creada el gateway a internet hay que conectarlo a una VPC seleccionando en acciones y 
