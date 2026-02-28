- Descripción

Este proyecto consiste en la creación, modificación, poblamiento y consulta de una base de datos para la gestión de un taller mecánico.

El script está diseñado para ejecutarse de forma secuencial respetando las dependencias y restricciones de integridad referencial.

- Estructura del Script
1️. Eliminación de objetos existentes

DROP TABLE con CASCADE CONSTRAINTS

DROP SEQUENCE

Se eliminan tablas y secuencias previas para evitar conflictos al ejecutar nuevamente el script.

2️. Creación de tablas

Se crean las siguientes tablas:

- PAIS

- CIUDAD

- SUCURSAL

- CLIENTE

- MECANICO

- AUTOMOVIL

- SERVICIO

- MANTENCION

- DETALLE_SERVICIO

Incluyen:

- Claves primarias

- Claves foráneas

- Restricciones CHECK

- Restricciones UNIQUE

3️. Poblamiento de datos

Se crean y utilizan las secuencias:

- SEQ_SERVICIO (inicia en 400, incrementa en 2)

- SEQ_CIUDAD (inicia en 165, incrementa en 5)

Se insertan datos según la información proporcionada en el documento oficial.
