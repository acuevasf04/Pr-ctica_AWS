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

Una vez seleccionado, entramos a la configuración del VPC y se configura el tipo de red que queremos implementar. En mi caso voy a poner una red con una máscara /24 por que no voy a usar muchos dispositivos dentro de la red.

<img width="1856" height="806" alt="imagen" src="https://github.com/user-attachments/assets/519ca796-6748-4949-92b0-b055e3bd0f42" />
