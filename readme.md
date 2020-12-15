[TOC]
# Aprendiendo C

## Introducción
C es un lenguaje de programación de bajo nivel, el cual se usa en sistemas embebidos, desarrollo de aplicaciones web (Backend), desarrollo de sistemas operativos, entre otras cosas. Es por todas estas razones que me propuse a documentar mi aprendizaje en el lenguaje C.

## Disclaimer
En este repositorio he utilizado jupyterlab, debido a que me parece una forma más interactiva para aprender y probar cosas, además que me permite agregar texto en formato markdown (*lo* usaré mucho para las notas). 

## Requerimientos
Para que el contenido de este repositorio te funcione *y puedas clonarlo* y modificar los archivos a tu conveniencia, existen 2 opciones:

1. Copiar y pegar el código de las celdas en archivos .c, usando tu editor de código favorito, compilar y ejecutar tus archivos por consola.

2. Utilizar Jupyterlab con el kernel de C para ejecutar cada una de las celdas (También sirve con Jupyter Notebook).

## Instalación y Uso
 
- **Opción 1:**
    1. Instalar gcc,  en Linux `sudo apt install build-essential`, en Mac se instala  `gcc` en la terminal e instalas con ayuda de Xcode.
    2. Descargar tu editor de texto favorito, en mi caso [VS Code](https://code.visualstudio.com/download).
    3. Abres VS Code, creas una nueva carpeta, aplasta `ctrl + shift + p`, se abrirá un buscador y escribes `Nuevo terminal integrado`, le das clic.
    4. Con el terminal abierto dentro de la carpeta que creaste, usas el comando `mkdir nombre-de-la-caperta` para crear una carpeta nueva.
    5. Luego de crear la carpeta usa el comando `cd nombre-de-la-carpeta`, esto te moverá dentro de la carpeta que creaste. Seguido de esto, usa el comando `touch nombre-del-archivo.c`.
    6. Abres el archivo dando clic sobre el. Copias y pegas el código que está en los notebooks.
    7. Para compilar usas el comando `gcc nombre-del-archivo.c`.
    8. Para ejecutar usas el comando `a.out`.

- **Opcion 2:**
    1. Descargar [Conda](https://www.anaconda.com/products/individual).
    2. Agregar conda al PATH (En muchos casos no se agrega automáticamente). 
    3. Crear un entorno virtual `conda create -n nombre-del-entorno`.
    4. Activar el entorno `conda activate nombre-del-entorno`.
    5. Instalar Jupyterlab `conda install -c conda-forge jupyterlab`.
    6. Instalar el kernel de C `pip install jupyter-c-kernel`.
    7. Abrir Jupyterlab `jupyterlab`.
    8. En la ventana New, creas un nuevo cuaderno con el compilador de C.

## Index
### Bases
### Tipos de datos
### Operadores
### Control de Flujo
### Bucles
### Arreglos
### Funciones
### Pointers
