~~Breve descripción (no más de 5 lineas) del proyecto y lo que apunta resolver.
Listado de funcionalidades (casos de uso)
Listado de actores/roles 
Listado de las entidades principales
Instrucciones técnicas:
    - Para la instalación de un entorno de desarrollo
    - Para la ejecución
Listado de los endpoints de la API~~ 

# Transportes Raffi
## Descripcion del proyecto
***El proyecto expone los endpoints de backend de un sistema de gestion de transporte de paqueteria. 
El objetivo es dar respuesta a la necesidad de un Cliente de proveer un mecanismo para enviar un paquete, para ello cuenta con interfaces de alta de Clientes, Chofer, Viajes.***

## Funcionalidades
* CRUD de Usuario
* CRUD de Chofer
* CRUD de Cliente
* CRUD de Viaje Programado
* Gestion de Hoja de Ruta
  * Consulta de Clima/Pronostico
  * Consulta de ruta

## Actores/Roles
* Administrador
* Observador

## Entidades
* Usuario
* Cliente
* Chofer
* Viaje

## Instalación

Usar el gestor de paquetes npm para instalar la aplicación.

```bash
npm install
```


## Ejecución
1.
2.
3.

## API endpoints
### /usuarios
Estos endpoints corresponden a la gestión de usuarios de la aplicación.

#### GET
`Obtener Usuarios` [/usuarios]<br/>
`Obtener Usuario` [/usuarios/:id]<br/>

#### POST
`Agregar Usuarios` [/usuarios]<br/>
`Login` [/usuarios/login]<br/>

#### PUT
`Modificar Usuario` [/usuarios/:id]<br/>

