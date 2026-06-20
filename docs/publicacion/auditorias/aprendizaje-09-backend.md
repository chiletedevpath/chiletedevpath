# Auditoria de Publicacion: aprendizaje/09-backend

| Campo | Detalle |
|---|---|
| Codigo | CDP-AUD-APR-009 |
| Version | 1.0 |
| Estado | Alineado para GitHub; requiere control de historial antes de web |
| Fecha | 19/06/2026 |
| Responsable | Adrian Pisco, fundador de Chilete DevPath |
| Revision tecnica | Chilete DevPath |

## 1. Alcance revisado

Se reviso la carpeta `aprendizaje/09-backend`, incluyendo:

- README principal;
- seccion `spring-boot`;
- proyectos `api-bd`, `api-crud`, `api-rest`, `apis-externas`, `hexagonal`, `seguridad` y `testing`;
- archivos `application.properties`;
- busqueda de carpetas generadas y posibles secretos.

## 2. Resultado

| Criterio | Resultado |
|---|---|
| Material privado de UTP, Tecsup, docente o evaluacion | No detectado en auditoria inicial |
| Datos personales de terceros | No detectado como datos reales; contiene modelos con email, telefono y DNI |
| Imagenes, marcas, logos o personajes de terceros | No aplica |
| Credenciales, tokens o rutas sensibles | Saneado en archivos actuales; revisar historial |
| Fuentes externas pendientes | Requiere revisar condiciones de APIs externas antes de web |
| Uso de IA declarado | No aplica en codigo; documentar si se convierte en guia web |
| Enfoque comunitario | Alineado para GitHub |
| Alineacion con politicas de Chilete DevPath | Alineado para GitHub con restriccion de historial |

## 3. Hallazgos criticos

La carpeta tiene valor tecnico porque contiene practicas reales de backend con Spring Boot, APIs, arquitectura hexagonal, seguridad, testing y consumo de APIs externas.

Sin embargo, no debe usarse para la web ni destacarse publicamente hasta confirmar:

- historial Git sin exposicion de secretos vigentes;
- rotacion o revocacion de cualquier token real usado anteriormente;
- condiciones de uso de APIs externas;
- variables de entorno documentadas por proyecto;
- ejemplos de DNI o datos personales solo como entradas ficticias.

No se registran los valores sensibles en este documento.

## 4. Decision

`aprendizaje/09-backend` puede mantenerse en GitHub como evidencia de aprendizaje backend.

Antes de usarlo en la web o destacarlo, se debe ejecutar una fase adicional:

- revisar historial si esos secretos ya fueron versionados;
- rotar o revocar tokens reales;
- documentar configuracion local segura por proyecto;
- validar ejecucion de cada modulo backend seleccionado.

## 5. Contenido que puede publicarse despues de saneamiento

- Explicacion de conceptos backend.
- Estructura de proyectos Spring Boot.
- Ejemplos de API REST, seguridad, testing y arquitectura hexagonal.
- Guias de ejecucion con variables de entorno.

## 6. Contenido que requiere ajuste antes de web

- Historial Git si hubo valores sensibles reales.
- Guias por modulo antes de publicacion web.
- Proyectos que consumen APIs externas.
- Modulos de seguridad y JWT.

## 7. Saneamiento aplicado

Se reemplazaron valores sensibles detectados en archivos actuales por variables de entorno:

- credenciales de base de datos;
- tokens de APIs externas;
- token de Sonar;
- clave de firma JWT.

Se reforzo:

- README principal de backend;
- README de Spring Boot;
- configuracion de SonarCloud con nombre alineado a Chilete DevPath;
- token de Vault como variable con valor vacio por defecto;
- comentario de token Bearer para evitar apariencia de secreto real.

Importante: si alguno de los valores anteriores fue real y ya estuvo versionado, debe revocarse o rotarse. El saneamiento del archivo actual no elimina exposicion en historial Git ni en remotos.

## 8. Decision para la web

| Estado | Decision |
|---|---|
| Publicable | Si, para GitHub |
| Requiere ajustes previos | Si, para version web |
| Mantener solo en GitHub | Recomendado hasta revisar historial e integraciones |
| No publicar | Configuraciones con tokens, claves o credenciales reales |
