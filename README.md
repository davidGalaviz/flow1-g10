# flow1-g10
Este repositorio contiene el primer ejercicio de NodeRed para el curso de internet de las cosas de Código IoT

## Introducción

Este erjercicio permite desmostar el uso de la pestaña de debug en NodeRed. Este ejercicio consiste en 
imprimir la fecha y hora cada segundo uniendo los siguentes nodos

- Inject

   > El nodo inject inyecta datos al flow ya sea manualmente o por un intervalo
- Debug

   > El nodo debug visualiza el proceso en la barra de debug

### Material Necesario

Para realizar este ejercicio necesitaras lo siguente

- [Ubuntu 20.04](https://ubuntu.com/download/desktop)
- [NodeJs](https://nodejs.org/en/)
  - [NPM](https://www.npmjs.com/)
  - [NodeRed](https://nodered.org/)

### Material de referencia

- [Instalación de Virtual Box](https://edu.codigoiot.com/course/view.php?id=810)
  - [Instalación de Ubuntu 20.04](https://edu.codigoiot.com/course/view.php?id=812)
- [Instalación de NodeRed](https://edu.codigoiot.com/course/view.php?id=817)
- [Intoducción a NodeRed](https://edu.codigoiot.com/course/view.php?id=278)

# Instrucciones

## Requisitos previos

1. Tener instalado todo el software listado en el **Material necesario**
2. Arrancar NodeRed escribiendo el comando `node-red` en la terminal
3. Abrir aplicacion de NodeRed en un navegador con la dirección ["http://localhost:1880"](http://localhost:1880/#flow/d0319225ca32761b)

## Instrucciones de ejecución

1. Se arrastra un nodo de **inject** y se configura de la siguente forma
   - msg.payload = timestamp
   - Repeat = interval
   - every 1 second
2. Se arrastra un nodo de **debug** 
3. Se conecta el nodo **inject** y el nodo **debug**
4. se guarda el flow oprimiendo el botón **Deploy**

# Resultados 

En la siguiente imagen pueden verse los resultados de este flow.

![resultados del flow](https://raw.githubusercontent.com/hugoescalpelo/flow1-NodeRed/main/Captura%20de%20pantalla%20del%20flow%201.png)

## Evidencias

[Repositorio](https://github.com/davidGalaviz/flow1-g10)

# Creditos

Desarrollado por David Galaviz

[GitHub](https://github.com/davidGalaviz)
