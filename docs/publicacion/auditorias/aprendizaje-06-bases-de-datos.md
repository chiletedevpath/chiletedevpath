# Auditoria de Publicacion: aprendizaje/06-bases-de-datos

| Campo | Detalle |
|---|---|
| Codigo | CDP-AUD-APR-006 |
| Version | 1.0 |
| Estado | Saneado con ajustes editoriales pendientes |
| Fecha | 19/06/2026 |
| Responsable | Adrian Pisco, fundador de Chilete DevPath |
| Revision tecnica | Chilete DevPath |

## 1. Alcance revisado

Se reviso la carpeta `aprendizaje/06-bases-de-datos`, incluyendo:

- README principal;
- secciones `modelado`, `mysql`, `postgresql` y `sql-server`;
- scripts `.sql`;
- diagramas `.dia`.

## 2. Resultado

| Criterio | Resultado |
|---|---|
| Material privado de UTP, Tecsup, docente o evaluacion | Riesgo bajo por ejercicio de participacion en clase |
| Datos personales de terceros | Riesgo medio si los datos de ejemplo no son ficticios |
| Imagenes, marcas, logos o personajes de terceros | No aplica |
| Credenciales, tokens o rutas sensibles | No detectado |
| Fuentes externas pendientes | Requiere contexto |
| Uso de IA declarado | No aplica en scripts; falta nota general si se documenta para web |
| Enfoque comunitario | Parcial |
| Alineacion con politicas de Chilete DevPath | Requiere ajustes |

## 3. Hallazgos

La seccion tiene valor para la web porque contiene modelado, SQL Server, DDL, DML, consultas y estructuras relacionales.

Antes de llevarla a la web, se deben revisar estos puntos:

- el README principal menciona `modeling`, pero la carpeta real es `modelado`;
- varios scripts usan campos como DNI, correo, telefono y direccion;
- algunos inserts usan correos y telefonos con apariencia real;
- existe un archivo llamado `04-participacion-clase.sql`, que debe tratarse como practica academica propia y no como material oficial;
- los README de MySQL y PostgreSQL estan en estado `En progreso`.

## 4. Decision

`aprendizaje/06-bases-de-datos` puede mantenerse en GitHub como evidencia de practica.

Para la futura web debe publicarse despues de mejorar documentacion, declarar datos ficticios y evitar presentar ejercicios de clase como material institucional.

## 5. Contenido que puede publicarse

- Conceptos de modelado entidad-relacion.
- Scripts DDL y DML revisados.
- Consultas SQL explicadas con datos ficticios.
- Comparacion introductoria entre SQL Server, MySQL y PostgreSQL.

## 6. Contenido que requiere ajuste antes de web

- README principal y README internos.
- Nota de datos ficticios.
- Correos, telefonos, DNI y direcciones de ejemplo.
- Archivo `04-participacion-clase.sql`, para documentarlo como practica propia o adaptada.
- Diagramas `.dia`, si se usaran como imagen o recurso descargable.

## 7. Saneamiento aplicado

Se neutralizaron correos, telefonos y nombres de ejemplo en los scripts SQL revisados.

Queda pendiente documentar de forma visible que los datos son ficticios y que `04-participacion-clase.sql` corresponde a una practica academica propia, no a material institucional oficial.

## 8. Decision para la web

| Estado | Decision |
|---|---|
| Publicable | Si, con ajustes |
| Requiere ajustes previos | Si |
| Mantener solo en GitHub | No necesariamente |
| No publicar | No |
