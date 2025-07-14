# PROYECTO API REST MiBanco

## Lenguajes y frameworks
C#
.NET Core 8.0 LTS


## Arquitectura
la arquitectura está dividida por capas, cada una con una unica responsabilidad.
se usa inyección de dependencias para no depender de implementaciones sino de interfaces

### Capa DAO
Esta capa se encarga del acceso a datos (archivos json)

### Capa Services
Esta capa se encarga de la logica de negocio, utilizando su dao correspondiente y sus metodos a fines

### Capa Controllers
Esta capa se sencarga de coordinar el flujo que el usuario lleva en la API

## Capa Helpers
aqui hay metodos auxiliares que se utilizan en algunos services


## Base de datos
Este proyecto no cuenta con una base de datos como tal, pero la simula mediante un hub de datos en un archivo .json

----------------------------------------------------------------------------------------------------------------

## Consideraciones
Importar el archivo postman para consultar los endpoints más comoda y rápidamente