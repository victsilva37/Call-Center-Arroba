# CALL CENTER ARROBA

#### Descripción del proyecto

Aplicación web interna utilizada por los equipos de call center para la gestión de ventas de planes de telefonía para la empresa Entel, permitiendo registrar operaciones, administrar comisiones y visualizar información según el rol del usuario.

El objetivo de Call Center Arroba es centralizar y ordenar el proceso de ventas, permitiendo el control de operaciones comerciales, la asignación de comisiones y la visualización de información según distintos niveles de rol.

### Detalles técnicos
| Característica       | Descripción                              |
|----------------------|------------------------------------------|
| Tipo de aplicación   | Aplicación web                           |
| Frontend             | (Por definir)                            |
| Backend              | (Por definir)                            |
| Lenguaje             | (Por definir)                            |
| Base de datos        | (Por definir)                            |

### Estructura del proyecto
(por definir)
### Funcionalidades principales

##### **Panel Principal**: 
Entrega una visión global del estado de la operación del call center y proporciona indicadores generales del sistema, junto con visualización de métricas como ventas por producto, ventas asociadas a comisiones y ventas pendientes de pago.

##### **Módulo de operaciones**: 
Permite a los ejecutivos ingresar ventas de planes de telefonía, además de proporcionar visualización y análisis de ventas, con opciones de búsqueda, filtros por producto y rangos de fecha.

Incluye las siguientes funciones:

* Ingreso manual de ventas de planes de telefonía por parte de los ejecutivos.
* Carga de archivos de ventas, permitiendo la incorporación de información proveniente de distintos orígenes.
* Carga de ventas masivas, orientada a procesar ventas enviadas por vendedores externos o equipos que no ingresan directamente al sistema.
* Cruce de archivos, funcionalidad destinada a comparar archivos entregados por la empresa operadora con los registros internos del sistema.
* Gestión de archivos TMZ, correspondientes a listados enviados por la operadora que contienen planes sin transacción asociada.

##### **Reportes**: 
El módulo de reportes permite la visualización de información relacionada con ventas y comisiones.

* Visualización de reportes de ventas según distintos criterios.
* Consulta de comisiones asociadas a las ventas registradas en el sistema.

##### **Módulo de Sistema**:
Agrupa los mantenedores y configuraciones base necesarias para el correcto funcionamiento de la aplicación. Está orientado principalmente a roles administrativos y de mayor jerarquía.

Este módulo interactúa directamente con entidades de la base de datos, permitiendo administrar parámetros clave del negocio y cuenta con las siguientes funciones:
* Gestión de usuarios.
* Asignación de roles según perfil.
* Visualización del estado de los usuarios.
* Gestión de comisiones.
* Ingreso y administración de comisiones.
* Definición de valores de comisión.

### Notas Adicionales
