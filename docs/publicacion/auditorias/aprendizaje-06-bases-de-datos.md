# Auditoria de Publicacion: aprendizaje/06-bases-de-datos

| Campo | Detalle |
|---|---|
| Codigo | CDP-AUD-APR-006 |
| Version | 1.0 |
| Estado | Alineado para GitHub; requiere seleccion para web |
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
| Material privado de UTP, Tecsup, docente o evaluacion | No detectado como material oficial; contiene practica academica propia |
| Datos personales de terceros | No detectado; los datos de ejemplo son ficticios |
| Imagenes, marcas, logos o personajes de terceros | No aplica |
| Credenciales, tokens o rutas sensibles | No detectado |
| Fuentes externas pendientes | No detectado, pero debe documentarse si se adapta contenido futuro |
| Uso de IA declarado | No aplica en scripts; falta nota general si se documenta para web |
| Enfoque comunitario | Alineado para GitHub |
| Alineacion con politicas de Chilete DevPath | Alineado para GitHub |

## 3. Hallazgos

La seccion tiene valor para la web porque contiene modelado, SQL Server, DDL, DML, consultas y estructuras relacionales.

Se mejoro:

- README principal;
- README de `modelado`, `mysql`, `postgresql` y `sql-server`;
- referencia correcta a la carpeta `modelado`;
- advertencia de ejecucion para scripts con `DROP`, `ALTER` y permisos;
- neutralizacion de marcas de productos en inserts;
- correccion de un `GRANT` mal escrito;
- ajuste de `04-participacion-clase.sql` para usar la tabla `Clientes`;
- eliminacion de `03-consultas-avanzadas.sql` por no aportar contenido real.

## 4. Decision

`aprendizaje/06-bases-de-datos` puede mantenerse en GitHub como evidencia de practica y ruta de aprendizaje.

Para la futura web, debe seleccionarse que scripts se convertiran en guias explicadas y evitar presentar ejercicios de clase como material institucional.

## 5. Contenido que puede publicarse

- Conceptos de modelado entidad-relacion.
- Scripts DDL y DML revisados.
- Consultas SQL explicadas con datos ficticios.
- Comparacion introductoria entre SQL Server, MySQL y PostgreSQL.

## 6. Contenido que requiere ajuste antes de web

- Seleccion de scripts para web.
- Explicacion de datos ficticios por ejercicio.
- Pruebas o capturas de ejecucion si se convierten en guias.
- Diagramas `.dia`, si se usaran como imagen o recurso descargable.

## 7. Saneamiento aplicado

Se neutralizaron correos, telefonos, nombres y productos de ejemplo en los scripts SQL revisados.

Se reforzaron README y se retiro un archivo sin proposito real.

## 8. Decision para la web

| Estado | Decision |
|---|---|
| Publicable | Si, para GitHub |
| Requiere ajustes previos | Solo para version web |
| Mantener solo en GitHub | No necesariamente |
| No publicar | No |
