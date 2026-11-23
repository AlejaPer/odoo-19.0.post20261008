# Proyecto de prácticas de Odoo 19
## Objetivo
El proceso resuelve problemas de gestión de empresas agrícolas. Las empresas que usen mi sismeta podrán introducir un mapa junto con las medidas
de cada campo de cultivo que tenga la empresa. Se podrá añadir que cultivos tiene cada uno, las fechas de riego, los trabajadores asignados
a cada campo en cada jornada laboral, características de los empleados (salario, rango, campo asignado, nombre, dni, numero de telefono). Se
podrán almacenar distintos tipos de frutas y verduras junto con las características de cada una (agua necesitada por semana aproximadamente,
tiempos de riego, etc). 

## Índice
- [Requisitos](#requisitos)
- [Estructura](#estructura)
- [Entorno de trabajo](#entorno-de-trabajo)
- [Arranque](#arranque)
- [Comprobaciones](#comprobaciones)
- [Incidencias](#incidencias)
## Requisitos
| Elemento | Versión utilizada o procedencia |
| --- | --- |
| Odoo | 19.0 Revision f35003a1 (2026-10-19) |
| Python | 3.14.4 |
| PostgreSQL | PSQL 18.6 |º
| Sistema | Ubuntu 26.04.1 LTS en WSL 2|
## Estructura
- `custom_addons/`: módulos desarrollados en clase.
- `docs/img/`: capturas de documentación sin datos privados.
- `requirements.txt`: dependencias de Python de referencia.
- `GUIA_PROYECTO.md`: instrucciones de este proyecto.
El código base de Odoo y `.venv/` no se incluyen en Git.
El README original de Odoo se conserva en la instalación.
El repositorio no contiene la base de datos ni el filestore.