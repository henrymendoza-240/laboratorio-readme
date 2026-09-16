# Sistema de Biblioteca Virtual
![Estado](https://img.shields.io/badge/estado-en%20desarrollo-yellow)
![Version](https://img.shields.io/badge/version-1.0.0-blue)
![Licencia](https://img.shields.io/badge/licencia-MIT-green)

Aplicacion web para la gestion y prestamo de libros digitales en linea.
Permite a los usuarios buscar catalogos, reservar libros y gestionar sus devoluciones de forma sencilla.

## Tabla de contenidos

- [Descripcion](#descripcion)
- [Instalacion](#instalacion)
- [Uso](#uso)
- [Estado de funcionalidades](#estado-de-funcionalidades)
- [Pendientes](#pendientes)
- [Arquitectura](#arquitectura)
- [Contribuidores](#contribuidores)

## Descripcion

El Sistema de Biblioteca Virtual es una plataforma desarrollada para digitalizar la busqueda y prestamo de libros. 
Su objetivo es facilitar el acceso al catalogo desde cualquier dispositivo.

## Instalacion

Ejecuta los siguientes comandos en la terminal para clonar e instalar el proyecto:

```bash
git clone [https://github.com/henrymendoza-240/laboratorio-readme.git](https://github.com/TU-USUARIO/laboratorio-readme.git)
cd laboratorio-readme
npm install
```
Uso
Para iniciar el servidor de desarrollo local:

``` Bash
npm start
```
# Estado de funcionalidades

| Función | Estado |
|---|---|
| Login | Listo |
| Reportes | En progreso |

## Pendientes

- [x] Diseño de la base de datos
- [ ] Pruebas unitarias

## Arquitectura

```mermaid
graph LR
    A[Usuario] --> B[Frontend]
    B --> C[API]
    C --> D[(Base de datos)]