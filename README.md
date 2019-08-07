# Cuestionario_crud

API CRUD para el manejo de las preguntas necesarias en los formularioa planteados en el sistema de gestion academica

## Requirements
Go version >= 1.8.

## Preparación:
    Para usar el API, usar el comando:
        - go get github.com/udistrital/cuestionario_crud

## Run

Definir los valores de las siguientes variables de entorno:

 - `API_CUESTIONARIO_HTTP_PORT`: Puerto asignado para la ejecución del API
 - `CUESTIONARIO_CRUD__PGUSER`: Usuario de la base de datos
 - `CUESTIONARIO_CRUD__PGPASS`: Clave del usuario para la conexión a la base de datos  
 - `CUESTIONARIO_CRUD__PGURLS`: Host de conexión
 - `CUESTIONARIO_CRUD__PGDB`: Nombre de la base de datos
 - `CUESTIONARIO_CRUD__SCHEMA`: Esquema a utilizar en la base de datos

Ejemplo: API_CUESTIONARIO_HTTP_PORT=8080 CUESTIONARIO_CRUD__PGUSER=postgres CUESTIONARIO_CRUD__PGPASS=12345678 CUESTIONARIO_CRUD__PGURLS=localhost CUESTIONARIO_CRUD__PGDB=informacion_familiar CUESTIONARIO_CRUD__SCHEMA=cuestionario bee run -downdoc=true -gendoc=true

## MODELO DE DATOS

Como modelos de datos del Api se utilizo el siguiente 

![image](https://github.com/udistrital/cuestionario_crud/blob/dev/cuestonario.png)